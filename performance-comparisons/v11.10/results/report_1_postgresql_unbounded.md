### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 1ms | 29ms | 28ms | 3221.34
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 13ms | 9ms | 211.52
| CommandWebhookStore.Cleanup | avg | 18ms | 45ms | 27ms | 150.34
| PostStore.AnalyticsPostCount | avg | 189ms | 473ms | 284ms | 149.88
| PostStore.GetPostIdAfterTime | avg | 5ms | 11ms | 6ms | 113.53
| SessionStore.GetSessionsExpired | avg | 6ms | 13ms | 7ms | 110.71
| PostPersistentNotificationStore.Get | avg | 7ms | 14ms | 7ms | 103.43
| PostStore.GetPostReminders | avg | 5ms | 10ms | 5ms | 97.11
| EmojiStore.GetMultipleByName | avg | 12ms | 24ms | 12ms | 96.59
| ThreadStore.MarkAllAsReadByTeam | avg | 7ms | 13ms | 6ms | 90.42
| JobStore.UpdateStatus | avg | 8ms | 15ms | 7ms | 88.96
| RoleStore.GetByNames | avg | 16ms | 29ms | 13ms | 79.40
| ChannelStore.GetMembers | avg | 16ms | 27ms | 11ms | 70.54
| TokenStore.Cleanup | avg | 17ms | 27ms | 10ms | 60.53
| BotStore.Get | avg | 7ms | 11ms | 4ms | 60.03
| ChannelBookmarkStore.Delete | avg | 24ms | 37ms | 13ms | 54.18
| JobStore.UpdateOptimistically | avg | 8ms | 12ms | 4ms | 50.15
| ChannelStore.AutocompleteInTeamForSearch | avg | 73ms | 104ms | 31ms | 42.54
| RoleStore.ChannelHigherScopedPermissions | avg | 9ms | 12ms | 3ms | 31.59
| TemporaryPostStore.GetExpiredPosts | avg | 13ms | 17ms | 4ms | 30.05
| UserStore.GetProfilesNotInChannel | avg | 13ms | 16ms | 3ms | 23.20
| UserStore.GetByUsername | avg | 14ms | 17ms | 3ms | 20.99
| ChannelBookmarkStore.Get | avg | 20ms | 24ms | 4ms | 20.15
| ProductNoticesStore.ClearOldNotices | avg | 44ms | 48ms | 4ms | 9.02
| TeamStore.GetTotalMemberCount | avg | 64ms | 68ms | 4ms | 6.27
| ChannelStore.UpdateSidebarCategories | avg | 91ms | 95ms | 4ms | 4.38
| ChannelStore.CreateDirectChannel | avg | 85ms | 88ms | 3ms | 3.53
| PostStore.SearchPostsForUser | avg | 301ms | 310ms | 9ms | 2.99
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 50ms | 45ms | 908.80
| CommandWebhookStore.Cleanup | p99 | 48ms | 245ms | 197ms | 406.19
| TokenStore.Cleanup | p99 | 48ms | 241ms | 193ms | 397.94
| PostPersistentNotificationStore.Get | p99 | 47ms | 154ms | 107ms | 225.26
| JobStore.UpdateStatus | p99 | 50ms | 155ms | 105ms | 211.53
| PostPersistentNotificationStore.DeleteExpired | p99 | 70ms | 202ms | 132ms | 188.57
| ChannelBookmarkStore.Delete | p99 | 98ms | 238ms | 140ms | 142.37
| UserStore.GetProfilesNotInChannel | p99 | 85ms | 192ms | 107ms | 125.15
| BotStore.Get | p99 | 45ms | 94ms | 49ms | 107.69
| ChannelStore.AutocompleteInTeamForSearch | p99 | 375ms | 751ms | 376ms | 100.36
| PostStore.GetPostReminders | p99 | 45ms | 90ms | 45ms | 99.17
| ThreadStore.MarkAllAsReadByTeam | p99 | 24ms | 48ms | 24ms | 98.97
| PostStore.AnalyticsPostCount | p99 | 496ms | 985ms | 489ms | 98.54
| SessionStore.GetSessionsExpired | p99 | 47ms | 92ms | 45ms | 96.75
| ChannelStore.UpdateSidebarCategories | p99 | 480ms | 873ms | 393ms | 81.80
| PostStore.GetPostIdAfterTime | p99 | 72ms | 96ms | 24ms | 33.12
| ChannelStore.CreateDirectChannel | p99 | 652ms | 746ms | 94ms | 14.41
| PostStore.GetPostsAfter | p99 | 165ms | 188ms | 23ms | 13.97
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 81ms | 90ms | 9ms | 11.04
| PostStore.SearchPostsForUser | p99 | 3.61s | 3.873s | 263ms | 7.29
| UserStore.Save | p99 | 546ms | 580ms | 34ms | 6.22
| UserStore.UpdateUpdateAt | p99 | 74ms | 78ms | 4ms | 5.40
| EmojiStore.GetMultipleByName | p99 | 93ms | 98ms | 5ms | 5.38
| FileInfoStore.GetForPost | p99 | 92ms | 96ms | 4ms | 4.36
| FileInfoStore.SetContent | p99 | 208ms | 217ms | 9ms | 4.33
| FileInfoStore.AttachToPost | p99 | 196ms | 204ms | 8ms | 4.08
| TemporaryPostStore.GetExpiredPosts | p99 | 93ms | 96ms | 3ms | 3.23
| ChannelStore.GetMembers | p99 | 95ms | 98ms | 3ms | 3.17
| TeamStore.GetTotalMemberCount | p99 | 228ms | 235ms | 7ms | 3.07
| StatusStore.SaveOrUpdateMany | p99 | 202ms | 208ms | 6ms | 2.97
| ChannelStore.SaveMember | p99 | 600ms | 612ms | 12ms | 2.00
| ProductNoticesStore.View | p99 | 890ms | 901ms | 11ms | 1.24
| UserStore.AutocompleteUsersInChannel | p99 | 384ms | 388ms | 4ms | 1.04
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 2ms | 0s | -2ms | -126.10
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 5ms | 0s | -5ms | -107.61
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -103.97
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 7ms | 0s | -7ms | -102.36
| JobStore.GetAllByTypePage | avg | 15ms | 0s | -15ms | -101.89
| UserStore.AnalyticsGetInactiveUsersCount | avg | 25ms | 0s | -25ms | -101.78
| ScheduledPostStore.Get | avg | 35ms | 0s | -35ms | -101.43
| TeamStore.AnalyticsTeamCount | avg | 38ms | 0s | -38ms | -100.91
| UserStore.AnalyticsActiveCount | avg | 37ms | 0s | -37ms | -99.71
| ChannelStore.GetMemberCountsByGroup | avg | 7ms | 0s | -7ms | -99.67
| ChannelStore.AnalyticsCountAll | avg | 35ms | 0s | -35ms | -99.55
| PostStore.AnalyticsPostCountByTeam | avg | 12ms | 0s | -12ms | -97.76
| LicenseStore.GetAll | avg | 5ms | 0s | -5ms | -95.48
| PostStore.GetPostIdBeforeTime | avg | 7ms | 0s | -7ms | -93.86
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | avg | 2ms | 0s | -2ms | -88.94
| ChannelStore.CreateSidebarCategory | avg | 47ms | 11ms | -36ms | -75.84
| UserStore.GetProfilesInChannel | avg | 17ms | 8ms | -9ms | -51.45
| ChannelBookmarkStore.UpdateSortOrder | avg | 47ms | 26ms | -21ms | -44.88
| PostStore.Delete | avg | 60ms | 37ms | -23ms | -38.20
| ChannelStore.GetMany | avg | 30ms | 19ms | -11ms | -36.12
| PostStore.SetPostReminder | avg | 23ms | 15ms | -8ms | -34.89
| PreferenceStore.DeleteCategoryAndName | avg | 15ms | 11ms | -4ms | -26.37
| UserStore.GetMany | avg | 16ms | 12ms | -4ms | -25.37
| StatusStore.UpdateExpiredDNDStatuses | avg | 13ms | 10ms | -3ms | -23.40
| LinkMetadataStore.Save | avg | 13ms | 10ms | -3ms | -22.52
| UserStore.Update | avg | 29ms | 23ms | -6ms | -21.04
| ScheduledPostStore.GetPendingScheduledPosts | avg | 15ms | 12ms | -3ms | -19.65
| ChannelStore.Save | avg | 50ms | 42ms | -8ms | -15.85
| ChannelBookmarkStore.Save | avg | 59ms | 50ms | -9ms | -15.25
| ReactionStore.GetForPost | avg | 14ms | 12ms | -2ms | -14.51
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 21ms | 18ms | -3ms | -14.10
| JobStore.GetNewestJobByStatusesAndType | avg | 14ms | 12ms | -2ms | -13.87
| ChannelStore.GetTeamChannels | avg | 53ms | 46ms | -7ms | -13.09
| TeamStore.GetActiveMemberCount | avg | 75ms | 67ms | -8ms | -10.70
| ChannelStore.GetSidebarCategory | avg | 32ms | 30ms | -2ms | -6.22
| ChannelStore.GetPublicChannelsForTeam | avg | 34ms | 32ms | -2ms | -5.95
| ChannelStore.SaveMember | avg | 73ms | 71ms | -2ms | -2.74
| UserStore.Save | avg | 174ms | 172ms | -2ms | -1.15
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| LicenseStore.GetAll | p99 | 25ms | 0s | -25ms | -101.83
| ChannelStore.GetMemberCountsByGroup | p99 | 25ms | 0s | -25ms | -101.83
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.00
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.92
| PostStore.AnalyticsPostCountByTeam | p99 | 25ms | 0s | -25ms | -100.60
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 25ms | 0s | -25ms | -100.60
| TeamStore.AnalyticsTeamCount | p99 | 50ms | 0s | -50ms | -100.50
| UserStore.AnalyticsActiveCount | p99 | 50ms | 0s | -50ms | -100.50
| ChannelStore.AnalyticsCountAll | p99 | 50ms | 0s | -50ms | -100.50
| PostStore.GetPostIdBeforeTime | p99 | 88ms | 0s | -88ms | -100.01
| ScheduledPostStore.Get | p99 | 98ms | 0s | -98ms | -100.00
| JobStore.GetAllByTypePage | p99 | 93ms | 0s | -93ms | -99.47
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 24ms | 0s | -24ms | -98.97
| UserStore.GetProfilesInChannel | p99 | 413ms | 77ms | -336ms | -81.45
| ChannelStore.CreateSidebarCategory | p99 | 234ms | 48ms | -186ms | -79.64
| ChannelBookmarkStore.Save | p99 | 845ms | 242ms | -603ms | -71.36
| ChannelBookmarkStore.UpdateSortOrder | p99 | 244ms | 99ms | -145ms | -59.43
| LinkMetadataStore.Save | p99 | 184ms | 77ms | -107ms | -58.16
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 194ms | 95ms | -99ms | -50.90
| ChannelStore.Save | p99 | 457ms | 248ms | -209ms | -45.68
| PostStore.Delete | p99 | 430ms | 242ms | -188ms | -43.72
| JobStore.UpdateStatusOptimistically | p99 | 165ms | 99ms | -66ms | -39.94
| JobStore.Save | p99 | 81ms | 49ms | -32ms | -39.59
| ChannelStore.GetMany | p99 | 230ms | 144ms | -86ms | -37.37
| PostStore.SetPostReminder | p99 | 229ms | 154ms | -75ms | -32.75
| JobStore.GetNewestJobByStatusesAndType | p99 | 196ms | 132ms | -64ms | -32.72
| PostPersistentNotificationStore.GetSingle | p99 | 167ms | 115ms | -52ms | -31.23
| ReactionStore.GetForPost | p99 | 168ms | 116ms | -52ms | -31.01
| ChannelStore.GetByName | p99 | 129ms | 100ms | -29ms | -22.44
| ThreadStore.GetTotalUnreadMentions | p99 | 138ms | 108ms | -30ms | -21.67
| ClusterDiscoveryStore.SetLastPingAt | p99 | 167ms | 131ms | -36ms | -21.53
| DraftStore.GetDraftsForUser | p99 | 187ms | 147ms | -40ms | -21.33
| StatusStore.Get | p99 | 149ms | 119ms | -30ms | -20.14
| ChannelStore.GetPinnedPostCount | p99 | 186ms | 149ms | -37ms | -19.87
| EmojiStore.GetByName | p99 | 161ms | 131ms | -30ms | -18.67
| ThreadStore.Get | p99 | 200ms | 163ms | -37ms | -18.45
| PostStore.Update | p99 | 287ms | 236ms | -51ms | -17.74
| PreferenceStore.GetAll | p99 | 119ms | 99ms | -20ms | -16.88
| ChannelStore.GetTeamChannels | p99 | 228ms | 191ms | -37ms | -16.21
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 162ms | 136ms | -26ms | -16.04
| TeamStore.GetTeamsByUserId | p99 | 116ms | 98ms | -18ms | -15.56
| JobStore.GetCountByStatusAndType | p99 | 218ms | 186ms | -32ms | -14.71
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 131ms | 112ms | -19ms | -14.53
| UserStore.GetUnreadCount | p99 | 160ms | 137ms | -23ms | -14.41
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 141ms | 121ms | -20ms | -14.21
| UserStore.IsEmpty | p99 | 57ms | 49ms | -8ms | -14.06
| ThreadStore.GetMembershipForUser | p99 | 173ms | 149ms | -24ms | -13.89
| JobStore.GetAllByStatus | p99 | 201ms | 175ms | -26ms | -12.92
| ChannelStore.GetSidebarCategory | p99 | 285ms | 249ms | -36ms | -12.63
| ChannelStore.GetGuestCount | p99 | 159ms | 139ms | -20ms | -12.61
| PreferenceStore.Get | p99 | 158ms | 140ms | -18ms | -11.39
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 247ms | 219ms | -28ms | -11.35
| ScheduledPostStore.CreateScheduledPost | p99 | 100ms | 89ms | -11ms | -11.04
| PropertyGroupStore.Get | p99 | 110ms | 98ms | -12ms | -10.91
| PostStore.GetEtag | p99 | 183ms | 164ms | -19ms | -10.38
| ChannelStore.GetAllChannelMembersForUser | p99 | 141ms | 127ms | -14ms | -9.96
| PropertyValueStore.SearchPropertyValues | p99 | 176ms | 159ms | -17ms | -9.67
| PostStore.GetPostsByThread | p99 | 173ms | 157ms | -16ms | -9.27
| ChannelStore.GetPublicChannelsForTeam | p99 | 248ms | 227ms | -21ms | -8.48
| ChannelStore.GetBoardChannel | p99 | 167ms | 153ms | -14ms | -8.39
| TeamStore.GetAllPage | p99 | 107ms | 98ms | -9ms | -8.39
| ThreadStore.GetThreadFollowers | p99 | 155ms | 142ms | -13ms | -8.38
| DraftStore.Upsert | p99 | 108ms | 99ms | -9ms | -8.31
| GroupStore.GetGroups | p99 | 168ms | 154ms | -14ms | -8.31
| FileInfoStore.Save | p99 | 109ms | 100ms | -9ms | -8.23
| FileInfoStore.GetByIds | p99 | 187ms | 172ms | -15ms | -8.02
| UserStore.Get | p99 | 145ms | 134ms | -11ms | -7.59
| PostStore.Get | p99 | 269ms | 249ms | -20ms | -7.44
| RoleStore.GetByNames | p99 | 168ms | 156ms | -12ms | -7.14
| FileInfoStore.Get | p99 | 170ms | 158ms | -12ms | -7.07
| ChannelStore.GetChannels | p99 | 191ms | 178ms | -13ms | -6.79
| ThreadStore.GetThreadUnreadReplyCount | p99 | 193ms | 180ms | -13ms | -6.73
| UserStore.GetProfilesByUsernames | p99 | 180ms | 168ms | -12ms | -6.65
| ThreadStore.GetThreadsForUser | p99 | 197ms | 184ms | -13ms | -6.61
| PostStore.GetPostsBefore | p99 | 186ms | 174ms | -12ms | -6.45
| TeamStore.Get | p99 | 156ms | 146ms | -10ms | -6.41
| PostStore.GetSingle | p99 | 159ms | 149ms | -10ms | -6.29
| StatusStore.GetByIds | p99 | 211ms | 198ms | -13ms | -6.17
| LinkMetadataStore.Get | p99 | 163ms | 153ms | -10ms | -6.14
| ChannelStore.GetMembersForUser | p99 | 182ms | 171ms | -11ms | -6.05
| PostPriorityStore.GetForPostWithContext | p99 | 152ms | 143ms | -9ms | -5.93
| ChannelStore.GetChannelUnread | p99 | 188ms | 177ms | -11ms | -5.86
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 104ms | 98ms | -6ms | -5.75
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 106ms | 100ms | -6ms | -5.67
| UserStore.GetProfileByIds | p99 | 182ms | 172ms | -10ms | -5.51
| UserStore.Update | p99 | 236ms | 223ms | -13ms | -5.51
| PostStore.GetPostReminderMetadata | p99 | 167ms | 158ms | -9ms | -5.40
| ChannelStore.GetFileCount | p99 | 153ms | 145ms | -8ms | -5.24
| ThreadStore.GetTeamsUnreadForUser | p99 | 201ms | 191ms | -10ms | -4.97
| SessionStore.Save | p99 | 189ms | 180ms | -9ms | -4.77
| ChannelStore.GetForPost | p99 | 210ms | 200ms | -10ms | -4.76
| ChannelStore.SearchGroupChannels | p99 | 201ms | 192ms | -9ms | -4.47
| UserStore.Count | p99 | 179ms | 171ms | -8ms | -4.46
| DraftStore.Get | p99 | 204ms | 195ms | -9ms | -4.41
| UserAccessTokenStore.GetByToken | p99 | 92ms | 88ms | -4ms | -4.36
| GroupStore.GetByName | p99 | 96ms | 92ms | -4ms | -4.19
| ChannelStore.GetChannelsByUser | p99 | 99ms | 95ms | -4ms | -4.05
| UserTermsOfServiceStore.GetByUser | p99 | 100ms | 96ms | -4ms | -4.00
| PostAcknowledgementStore.GetForPost | p99 | 151ms | 145ms | -6ms | -3.96
| ChannelStore.GetMemberForPost | p99 | 233ms | 224ms | -9ms | -3.87
| WebhookStore.GetOutgoingByTeam | p99 | 209ms | 201ms | -8ms | -3.83
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 216ms | 208ms | -8ms | -3.70
| UserStore.GetAllProfiles | p99 | 88ms | 85ms | -3ms | -3.42
| ThreadStore.GetThreadForUser | p99 | 236ms | 228ms | -8ms | -3.40
| ThreadStore.MarkAllAsReadByChannels | p99 | 94ms | 91ms | -3ms | -3.20
| PropertyFieldStore.SearchPropertyFields | p99 | 95ms | 92ms | -3ms | -3.17
| DraftStore.Delete | p99 | 98ms | 95ms | -3ms | -3.07
| UserStore.GetForLogin | p99 | 98ms | 95ms | -3ms | -3.07
| UserStore.GetMany | p99 | 166ms | 161ms | -5ms | -3.01
| ChannelStore.Get | p99 | 234ms | 227ms | -7ms | -2.99
| PostAcknowledgementStore.GetForPosts | p99 | 243ms | 237ms | -6ms | -2.47
| SystemStore.GetByName | p99 | 87ms | 85ms | -2ms | -2.29
| PostStore.GetPosts | p99 | 91ms | 89ms | -2ms | -2.20
| ChannelBookmarkStore.Get | p99 | 228ms | 223ms | -5ms | -2.19
| PostStore.Save | p99 | 375ms | 367ms | -8ms | -2.13
| StatusStore.UpdateExpiredDNDStatuses | p99 | 94ms | 92ms | -2ms | -2.13
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 95ms | 93ms | -2ms | -2.10
| ChannelStore.CreateInitialSidebarCategories | p99 | 384ms | 376ms | -8ms | -2.08
| PostPriorityStore.GetForPosts | p99 | 244ms | 239ms | -5ms | -2.05
| ThreadStore.GetTotalUnreadThreads | p99 | 99ms | 97ms | -2ms | -2.02
| TeamStore.GetTeamsForUser | p99 | 99ms | 97ms | -2ms | -2.01
| PostStore.GetPostsSince | p99 | 230ms | 226ms | -4ms | -1.74
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | avg | 30ms | 163ms | 133ms | 447.89
| getChannelMembers | avg | 16ms | 31ms | 15ms | 92.63
| updateReadStateAllThreadsByUser | avg | 7ms | 13ms | 6ms | 89.06
| autocompleteChannelsForTeamForSearch | avg | 73ms | 104ms | 31ms | 42.21
| followThreadByUser | avg | 69ms | 85ms | 16ms | 23.11
| updatePreferences | avg | 38ms | 40ms | 2ms | 5.33
| searchPostsInTeam | avg | 337ms | 345ms | 8ms | 2.37
| updateCategoriesForTeamForUser | avg | 168ms | 170ms | 2ms | 1.19
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | p99 | 50ms | 249ms | 199ms | 400.97
| followThreadByUser | p99 | 685ms | 1.915s | 1.23s | 179.57
| autocompleteChannelsForTeamForSearch | p99 | 383ms | 751ms | 368ms | 96.08
| updateCategoriesForTeamForUser | p99 | 1.09s | 2.117s | 1.027s | 94.24
| removeUserCustomStatus | p99 | 1.125s | 1.969s | 844ms | 75.03
| getTeamMember | p99 | 137ms | 151ms | 14ms | 10.25
| searchAllChannels | p99 | 248ms | 271ms | 23ms | 9.28
| getPostsForChannelAroundLastUnread | p99 | 494ms | 526ms | 32ms | 6.47
| getChannelMembers | p99 | 95ms | 99ms | 4ms | 4.23
| searchPostsInTeam | p99 | 3.993s | 4.098s | 105ms | 2.63
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 8ms | 0s | -8ms | -104.73
| getUsersByGroupChannelIds | avg | 5ms | 0s | -5ms | -102.03
| getServerLimits | avg | 25ms | 0s | -25ms | -101.55
| getJobsByType | avg | 15ms | 0s | -15ms | -100.91
| getConfig | avg | 34ms | 0s | -34ms | -100.28
| getFilteredUsersStats | avg | 17ms | 0s | -17ms | -99.61
| createEmoji | avg | 7ms | 0s | -7ms | -98.20
| deleteScheduledPost | avg | 6ms | 0s | -6ms | -97.65
| channelMemberCountsByGroup | avg | 3ms | 0s | -3ms | -95.82
| getPropertyFields | avg | 5ms | 0s | -5ms | -94.67
| getPrevTrialLicense | avg | 5ms | 0s | -5ms | -91.33
| createCategoryForTeamForUser | avg | 63ms | 19ms | -44ms | -69.72
| updateChannelBookmarkSortOrder | avg | 65ms | 26ms | -39ms | -59.71
| updateChannelBookmark | avg | 76ms | 33ms | -43ms | -56.87
| deletePost | avg | 125ms | 64ms | -61ms | -48.94
| createChannelBookmark | avg | 110ms | 71ms | -39ms | -35.53
| setPostReminder | avg | 130ms | 96ms | -34ms | -26.06
| createChannel | avg | 688ms | 513ms | -175ms | -25.44
| getChannel | avg | 32ms | 24ms | -8ms | -25.34
| patchPost | avg | 145ms | 118ms | -27ms | -18.68
| getTeamStats | avg | 91ms | 76ms | -15ms | -16.42
| getDrafts | avg | 18ms | 16ms | -2ms | -11.23
| getChannelUnread | avg | 18ms | 16ms | -2ms | -11.21
| logout | avg | 142ms | 127ms | -15ms | -10.58
| listCPAValues | avg | 31ms | 29ms | -2ms | -6.50
| saveReaction | avg | 70ms | 67ms | -3ms | -4.30
| createDirectChannel | avg | 584ms | 559ms | -25ms | -4.28
| getProfileImage | avg | 74ms | 72ms | -2ms | -2.72
| createPost | avg | 729ms | 710ms | -19ms | -2.60
| addTeamMember | avg | 1.392s | 1.357s | -35ms | -2.51
| createGroupChannel | avg | 962ms | 940ms | -22ms | -2.29
| createUser | avg | 414ms | 408ms | -6ms | -1.45
| updateReadStateThreadByUser | avg | 155ms | 153ms | -2ms | -1.29
| removeUserCustomStatus | avg | 356ms | 352ms | -4ms | -1.12
| getPostsForChannel | avg | 188ms | 186ms | -2ms | -1.06
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 25ms | 0s | -25ms | -101.83
| getPropertyFields | p99 | 10ms | 0s | -10ms | -101.52
| getServerLimits | p99 | 50ms | 0s | -50ms | -101.01
| getAgentsStatus | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getAgents | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -100.97
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -100.92
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| getRolesByNames | p99 | 10ms | 0s | -10ms | -100.50
| getConfig | p99 | 50ms | 0s | -50ms | -100.50
| deleteScheduledPost | p99 | 10ms | 0s | -10ms | -100.50
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| getJobsByType | p99 | 93ms | 0s | -93ms | -99.47
| updateChannelBookmark | p99 | 935ms | 98ms | -837ms | -89.52
| createChannelBookmark | p99 | 2.155s | 245ms | -1.91s | -88.63
| createCategoryForTeamForUser | p99 | 473ms | 97ms | -376ms | -79.58
| deletePost | p99 | 2.08s | 444ms | -1.636s | -78.65
| updateChannelBookmarkSortOrder | p99 | 244ms | 99ms | -145ms | -59.43
| setPostReminder | p99 | 930ms | 468ms | -462ms | -49.68
| createChannel | p99 | 4.275s | 2.354s | -1.921s | -44.93
| logout | p99 | 1.51s | 840ms | -670ms | -44.36
| getTeamStats | p99 | 428ms | 242ms | -186ms | -43.51
| patchPost | p99 | 1.555s | 888ms | -667ms | -42.90
| getChannel | p99 | 396ms | 231ms | -165ms | -41.71
| getTeamsForUser | p99 | 132ms | 100ms | -32ms | -24.29
| updateReadStateThreadByUser | p99 | 1.355s | 1.125s | -230ms | -16.97
| getPreferences | p99 | 143ms | 123ms | -20ms | -14.01
| addChannelMember | p99 | 2.861s | 2.488s | -373ms | -13.04
| listCPAValues | p99 | 315ms | 275ms | -40ms | -12.71
| getTeamMembersForUser | p99 | 145ms | 129ms | -16ms | -11.05
| createSchedulePost | p99 | 172ms | 155ms | -17ms | -9.88
| getChannelUnread | p99 | 218ms | 198ms | -20ms | -9.16
| getDrafts | p99 | 208ms | 189ms | -19ms | -9.13
| getPublicChannelsForTeam | p99 | 248ms | 230ms | -18ms | -7.27
| getAllTeams | p99 | 166ms | 154ms | -12ms | -7.22
| saveReaction | p99 | 467ms | 434ms | -33ms | -7.07
| listChannelBookmarksForChannel | p99 | 175ms | 164ms | -11ms | -6.30
| getChannelsForUser | p99 | 104ms | 98ms | -6ms | -5.75
| getUserStatusesByIds | p99 | 93ms | 88ms | -5ms | -5.36
| getPostThread | p99 | 802ms | 762ms | -40ms | -4.99
| getChannelsForTeamForUser | p99 | 201ms | 191ms | -10ms | -4.97
| getChannelMembersForTeamForUser | p99 | 191ms | 182ms | -9ms | -4.72
| getThreadsForUser | p99 | 213ms | 203ms | -10ms | -4.70
| getChannelStats | p99 | 153ms | 146ms | -7ms | -4.57
| updatePreferences | p99 | 371ms | 355ms | -16ms | -4.31
| viewChannel | p99 | 744ms | 713ms | -31ms | -4.17
| getUsersByNames | p99 | 194ms | 186ms | -8ms | -4.13
| getCategoriesForTeamForUser | p99 | 226ms | 217ms | -9ms | -3.98
| getChannelMembersForUser | p99 | 114ms | 110ms | -4ms | -3.52
| unfollowThreadByUser | p99 | 467ms | 451ms | -16ms | -3.43
| getTeamScheduledPosts | p99 | 217ms | 210ms | -7ms | -3.22
| getFileThumbnail | p99 | 374ms | 362ms | -12ms | -3.21
| searchGroupChannels | p99 | 207ms | 201ms | -6ms | -2.90
| upsertDraft | p99 | 209ms | 203ms | -6ms | -2.87
| createPost | p99 | 4.594s | 4.465s | -129ms | -2.81
| deleteDraft | p99 | 217ms | 211ms | -6ms | -2.76
| createGroupChannel | p99 | 4.723s | 4.593s | -130ms | -2.75
| getPostsForChannel | p99 | 2.374s | 2.317s | -57ms | -2.40
| root | p99 | 223ms | 219ms | -4ms | -1.80
| getTeamsUnreadForUser | p99 | 238ms | 234ms | -4ms | -1.68
| getFilePreview | p99 | 420ms | 414ms | -6ms | -1.43
| listCPAFields | p99 | 226ms | 223ms | -3ms | -1.33
| getUser | p99 | 248ms | 245ms | -3ms | -1.21
| createDirectChannel | p99 | 2.5s | 2.473s | -27ms | -1.08
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 87ms | 0s | 0.000
| BotStore.Get |  Avg| 7ms| 11ms | 4ms | 60.026
| |  P99| 45ms| 94ms | 49ms | 107.692
| ChannelBookmarkStore.Delete |  Avg| 24ms| 37ms | 13ms | 54.178
| |  P99| 98ms| 238ms | 140ms | 142.373
| ChannelBookmarkStore.Get |  Avg| 20ms| 24ms | 4ms | 20.152
| |  P99| 228ms| 223ms | -5ms | -2.191
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 12ms| 11ms | -1ms | -8.625
| |  P99| 131ms| 112ms | -19ms | -14.527
| ChannelBookmarkStore.Save |  Avg| 59ms| 50ms | -9ms | -15.253
| |  P99| 845ms| 242ms | -603ms | -71.363
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 47ms| 26ms | -21ms | -44.878
| |  P99| 244ms| 99ms | -145ms | -59.426
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 75ms | -1ms | -1.319
| ChannelStore.AnalyticsCountAll |  Avg| 35ms| 0s | -35ms | -99.549
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.Autocomplete |  Avg| 54ms| 53ms | -1ms | -1.847
| |  P99| 245ms| 247ms | 2ms | 0.817
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 73ms| 104ms | 31ms | 42.540
| |  P99| 375ms| 751ms | 376ms | 100.362
| ChannelStore.CreateDirectChannel |  Avg| 85ms| 88ms | 3ms | 3.527
| |  P99| 652ms| 746ms | 94ms | 14.406
| ChannelStore.CreateInitialSidebarCategories |  Avg| 33ms| 32ms | -1ms | -3.041
| |  P99| 384ms| 376ms | -8ms | -2.082
| ChannelStore.CreateSidebarCategory |  Avg| 47ms| 11ms | -36ms | -75.840
| |  P99| 234ms| 48ms | -186ms | -79.644
| ChannelStore.Get |  Avg| 23ms| 22ms | -1ms | -4.388
| |  P99| 234ms| 227ms | -7ms | -2.985
| ChannelStore.GetAllChannelMembersForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 141ms| 127ms | -14ms | -9.958
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 25ms| 24ms | -1ms | -3.956
| |  P99| 247ms| 219ms | -28ms | -11.346
| ChannelStore.GetBoardChannel |  Avg| 14ms| 13ms | -1ms | -7.311
| |  P99| 167ms| 153ms | -14ms | -8.391
| ChannelStore.GetByName |  Avg| 14ms| 13ms | -1ms | -7.146
| |  P99| 129ms| 100ms | -29ms | -22.442
| ChannelStore.GetChannelUnread |  Avg| 16ms| 15ms | -1ms | -6.173
| |  P99| 188ms| 177ms | -11ms | -5.864
| ChannelStore.GetChannels |  Avg| 16ms| 15ms | -1ms | -6.336
| |  P99| 191ms| 178ms | -13ms | -6.791
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 10ms | -1ms | -9.329
| |  P99| 99ms| 95ms | -4ms | -4.054
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 141ms| 121ms | -20ms | -14.206
| ChannelStore.GetFileCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 153ms| 145ms | -8ms | -5.244
| ChannelStore.GetForPost |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 210ms| 200ms | -10ms | -4.760
| ChannelStore.GetGuestCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 159ms| 139ms | -20ms | -12.607
| ChannelStore.GetMany |  Avg| 30ms| 19ms | -11ms | -36.124
| |  P99| 230ms| 144ms | -86ms | -37.371
| ChannelStore.GetMember |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 92ms | -1ms | -1.076
| ChannelStore.GetMemberCount |  Avg| 36ms| 37ms | 1ms | 2.750
| |  P99| 226ms| 226ms | 0s | 0.000
| ChannelStore.GetMemberCountsByGroup |  Avg| 7ms| 0s | -7ms | -99.668
| |  P99| 25ms| 0s | -25ms | -101.832
| ChannelStore.GetMemberForPost |  Avg| 41ms| 40ms | -1ms | -2.450
| |  P99| 233ms| 224ms | -9ms | -3.866
| ChannelStore.GetMemberLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 93ms | 1ms | 1.082
| ChannelStore.GetMembers |  Avg| 16ms| 27ms | 11ms | 70.544
| |  P99| 95ms| 98ms | 3ms | 3.175
| ChannelStore.GetMembersForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 182ms| 171ms | -11ms | -6.046
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 7ms| 0s | -7ms | -102.358
| |  P99| 24ms| 0s | -24ms | -98.969
| ChannelStore.GetMembersForUserWithPagination |  Avg| 12ms| 11ms | -1ms | -8.635
| |  P99| 100ms| 99ms | -1ms | -1.001
| ChannelStore.GetPinnedPostCount |  Avg| 14ms| 13ms | -1ms | -7.222
| |  P99| 186ms| 149ms | -37ms | -19.871
| ChannelStore.GetPublicChannelsForTeam |  Avg| 34ms| 32ms | -2ms | -5.950
| |  P99| 248ms| 227ms | -21ms | -8.484
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 216ms| 208ms | -8ms | -3.704
| ChannelStore.GetSidebarCategory |  Avg| 32ms| 30ms | -2ms | -6.223
| |  P99| 285ms| 249ms | -36ms | -12.634
| ChannelStore.GetTeamChannels |  Avg| 53ms| 46ms | -7ms | -13.089
| |  P99| 228ms| 191ms | -37ms | -16.210
| ChannelStore.IncrementMentionCount |  Avg| 9ms| 8ms | -1ms | -11.751
| |  P99| 91ms| 91ms | 0s | 0.000
| ChannelStore.Save |  Avg| 50ms| 42ms | -8ms | -15.851
| |  P99| 457ms| 248ms | -209ms | -45.683
| ChannelStore.SaveMember |  Avg| 73ms| 71ms | -2ms | -2.738
| |  P99| 600ms| 612ms | 12ms | 2.002
| ChannelStore.SearchGroupChannels |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 201ms| 192ms | -9ms | -4.473
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.104
| ChannelStore.UpdateSidebarCategories |  Avg| 91ms| 95ms | 4ms | 4.381
| |  P99| 480ms| 873ms | 393ms | 81.804
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 91ms | -1ms | -1.088
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 167ms| 131ms | -36ms | -21.532
| CommandWebhookStore.Cleanup |  Avg| 18ms| 45ms | 27ms | 150.336
| |  P99| 48ms| 245ms | 197ms | 406.188
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 29ms | 28ms | 3221.342
| |  P99| 5ms| 50ms | 45ms | 908.799
| DraftStore.Delete |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 95ms | -3ms | -3.071
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 21ms| 18ms | -3ms | -14.101
| |  P99| 97ms| 96ms | -1ms | -1.036
| DraftStore.Get |  Avg| 17ms| 16ms | -1ms | -5.969
| |  P99| 204ms| 195ms | -9ms | -4.412
| DraftStore.GetDraftsForUser |  Avg| 16ms| 15ms | -1ms | -6.115
| |  P99| 187ms| 147ms | -40ms | -21.334
| DraftStore.Upsert |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 108ms| 99ms | -9ms | -8.314
| EmojiStore.GetByName |  Avg| 13ms| 12ms | -1ms | -7.736
| |  P99| 161ms| 131ms | -30ms | -18.668
| EmojiStore.GetMultipleByName |  Avg| 12ms| 24ms | 12ms | 96.593
| |  P99| 93ms| 98ms | 5ms | 5.376
| FileInfoStore.AttachToPost |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 196ms| 204ms | 8ms | 4.082
| FileInfoStore.Get |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 170ms| 158ms | -12ms | -7.067
| FileInfoStore.GetByIds |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 187ms| 172ms | -15ms | -8.022
| FileInfoStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 96ms | 4ms | 4.359
| FileInfoStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 109ms| 100ms | -9ms | -8.227
| FileInfoStore.SetContent |  Avg| 22ms| 21ms | -1ms | -4.645
| |  P99| 208ms| 217ms | 9ms | 4.330
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 9ms| 8ms | -1ms | -11.709
| |  P99| 92ms| 91ms | -1ms | -1.090
| GroupStore.GetByName |  Avg| 10ms| 9ms | -1ms | -10.371
| |  P99| 96ms| 92ms | -4ms | -4.187
| GroupStore.GetGroups |  Avg| 14ms| 13ms | -1ms | -7.392
| |  P99| 168ms| 154ms | -14ms | -8.311
| JobStore.GetAllByStatus |  Avg| 16ms| 15ms | -1ms | -6.216
| |  P99| 201ms| 175ms | -26ms | -12.921
| JobStore.GetAllByTypePage |  Avg| 15ms| 0s | -15ms | -101.893
| |  P99| 93ms| 0s | -93ms | -99.466
| JobStore.GetCountByStatusAndType |  Avg| 17ms| 16ms | -1ms | -5.901
| |  P99| 218ms| 186ms | -32ms | -14.713
| JobStore.GetNewestJobByStatusesAndType |  Avg| 14ms| 12ms | -2ms | -13.872
| |  P99| 196ms| 132ms | -64ms | -32.716
| JobStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 81ms| 49ms | -32ms | -39.588
| JobStore.UpdateOptimistically |  Avg| 8ms| 12ms | 4ms | 50.146
| |  P99| 85ms| 84ms | -1ms | -1.170
| JobStore.UpdateStatus |  Avg| 8ms| 15ms | 7ms | 88.958
| |  P99| 50ms| 155ms | 105ms | 211.528
| JobStore.UpdateStatusOptimistically |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 165ms| 99ms | -66ms | -39.940
| LicenseStore.GetAll |  Avg| 5ms| 0s | -5ms | -95.484
| |  P99| 25ms| 0s | -25ms | -101.833
| LinkMetadataStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 163ms| 153ms | -10ms | -6.139
| LinkMetadataStore.Save |  Avg| 13ms| 10ms | -3ms | -22.518
| |  P99| 184ms| 77ms | -107ms | -58.156
| PostAcknowledgementStore.GetForPost |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 151ms| 145ms | -6ms | -3.962
| PostAcknowledgementStore.GetForPosts |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 243ms| 237ms | -6ms | -2.467
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 13ms | 9ms | 211.521
| |  P99| 70ms| 202ms | 132ms | 188.574
| PostPersistentNotificationStore.Get |  Avg| 7ms| 14ms | 7ms | 103.435
| |  P99| 47ms| 154ms | 107ms | 225.264
| PostPersistentNotificationStore.GetSingle |  Avg| 11ms| 10ms | -1ms | -9.012
| |  P99| 167ms| 115ms | -52ms | -31.229
| PostPriorityStore.GetForPostWithContext |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 152ms| 143ms | -9ms | -5.931
| PostPriorityStore.GetForPosts |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 244ms| 239ms | -5ms | -2.050
| PostStore.AnalyticsPostCount |  Avg| 189ms| 473ms | 284ms | 149.877
| |  P99| 496ms| 985ms | 489ms | 98.539
| PostStore.AnalyticsPostCountByTeam |  Avg| 12ms| 0s | -12ms | -97.758
| |  P99| 25ms| 0s | -25ms | -100.604
| PostStore.Delete |  Avg| 60ms| 37ms | -23ms | -38.198
| |  P99| 430ms| 242ms | -188ms | -43.722
| PostStore.Get |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 269ms| 249ms | -20ms | -7.438
| PostStore.GetEtag |  Avg| 15ms| 14ms | -1ms | -6.780
| |  P99| 183ms| 164ms | -19ms | -10.377
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 11ms | 6ms | 113.530
| |  P99| 72ms| 96ms | 24ms | 33.116
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 0s | -7ms | -93.863
| |  P99| 88ms| 0s | -88ms | -100.009
| PostStore.GetPostReminderMetadata |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 167ms| 158ms | -9ms | -5.397
| PostStore.GetPostReminders |  Avg| 5ms| 10ms | 5ms | 97.107
| |  P99| 45ms| 90ms | 45ms | 99.174
| PostStore.GetPosts |  Avg| 10ms| 9ms | -1ms | -10.376
| |  P99| 91ms| 89ms | -2ms | -2.199
| PostStore.GetPostsAfter |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 165ms| 188ms | 23ms | 13.974
| PostStore.GetPostsBefore |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 186ms| 174ms | -12ms | -6.448
| PostStore.GetPostsByThread |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 173ms| 157ms | -16ms | -9.272
| PostStore.GetPostsSince |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 230ms| 226ms | -4ms | -1.738
| PostStore.GetSingle |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 159ms| 149ms | -10ms | -6.287
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 375ms| 367ms | -8ms | -2.134
| PostStore.SearchPostsForUser |  Avg| 301ms| 310ms | 9ms | 2.989
| |  P99| 3.61s| 3.873s | 263ms | 7.286
| PostStore.SetPostReminder |  Avg| 23ms| 15ms | -8ms | -34.889
| |  P99| 229ms| 154ms | -75ms | -32.751
| PostStore.Update |  Avg| 34ms| 33ms | -1ms | -2.914
| |  P99| 287ms| 236ms | -51ms | -17.741
| PreferenceStore.DeleteCategoryAndName |  Avg| 15ms| 11ms | -4ms | -26.373
| |  P99| 93ms| 93ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 158ms| 140ms | -18ms | -11.385
| PreferenceStore.GetAll |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 119ms| 99ms | -20ms | -16.876
| PreferenceStore.Save |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 243ms| 244ms | 1ms | 0.411
| ProductNoticesStore.ClearOldNotices |  Avg| 44ms| 48ms | 4ms | 9.025
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 93ms| 92ms | -1ms | -1.078
| |  P99| 890ms| 901ms | 11ms | 1.236
| PropertyFieldStore.SearchPropertyFields |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 92ms | -3ms | -3.172
| PropertyGroupStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 110ms| 98ms | -12ms | -10.913
| PropertyValueStore.SearchPropertyValues |  Avg| 14ms| 13ms | -1ms | -7.167
| |  P99| 176ms| 159ms | -17ms | -9.672
| ReactionStore.GetForPost |  Avg| 14ms| 12ms | -2ms | -14.512
| |  P99| 168ms| 116ms | -52ms | -31.012
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -103.971
| |  P99| 5ms| 0s | -5ms | -101.002
| RetentionPolicyStore.GetCount |  Avg| 2ms| 0s | -2ms | -126.096
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 9ms| 12ms | 3ms | 31.587
| |  P99| 49ms| 48ms | -1ms | -2.029
| RoleStore.GetByNames |  Avg| 16ms| 29ms | 13ms | 79.404
| |  P99| 168ms| 156ms | -12ms | -7.142
| ScheduledPostStore.CreateScheduledPost |  Avg| 14ms| 13ms | -1ms | -7.013
| |  P99| 100ms| 89ms | -11ms | -11.037
| ScheduledPostStore.Get |  Avg| 35ms| 0s | -35ms | -101.431
| |  P99| 98ms| 0s | -98ms | -100.003
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 15ms| 12ms | -3ms | -19.655
| |  P99| 194ms| 95ms | -99ms | -50.900
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 93ms | -2ms | -2.102
| ScheduledPostStore.PermanentlyDeleteScheduledPosts |  Avg| 2ms| 0s | -2ms | -88.938
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 81ms| 90ms | 9ms | 11.043
| SessionStore.Get |  Avg| 19ms| 18ms | -1ms | -5.395
| |  P99| 214ms| 212ms | -2ms | -0.935
| SessionStore.GetLRUSessions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.096
| SessionStore.GetSessionsExpired |  Avg| 6ms| 13ms | 7ms | 110.710
| |  P99| 47ms| 92ms | 45ms | 96.751
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 162ms| 136ms | -26ms | -16.042
| SessionStore.Remove |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 67ms| 68ms | 1ms | 1.492
| SessionStore.Save |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 189ms| 180ms | -9ms | -4.768
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.095
| StatusStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 149ms| 119ms | -30ms | -20.136
| StatusStore.GetByIds |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 211ms| 198ms | -13ms | -6.175
| StatusStore.SaveOrUpdate |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| StatusStore.SaveOrUpdateMany |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 202ms| 208ms | 6ms | 2.974
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 13ms| 10ms | -3ms | -23.399
| |  P99| 94ms| 92ms | -2ms | -2.126
| StatusStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 92ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 7ms| 6ms | -1ms | -15.100
| |  P99| 87ms| 85ms | -2ms | -2.291
| TeamStore.AnalyticsTeamCount |  Avg| 38ms| 0s | -38ms | -100.912
| |  P99| 50ms| 0s | -50ms | -100.503
| TeamStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 156ms| 146ms | -10ms | -6.408
| TeamStore.GetActiveMemberCount |  Avg| 75ms| 67ms | -8ms | -10.704
| |  P99| 235ms| 235ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 11ms| 10ms | -1ms | -9.415
| |  P99| 107ms| 98ms | -9ms | -8.387
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 106ms| 100ms | -6ms | -5.673
| TeamStore.GetMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 87ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 11ms| 10ms | -1ms | -9.187
| |  P99| 116ms| 98ms | -18ms | -15.557
| TeamStore.GetTeamsForUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 97ms | -2ms | -2.015
| TeamStore.GetTotalMemberCount |  Avg| 64ms| 68ms | 4ms | 6.269
| |  P99| 228ms| 235ms | 7ms | 3.067
| TeamStore.SaveMember |  Avg| 40ms| 40ms | 0s | 0.000
| |  P99| 245ms| 247ms | 2ms | 0.817
| TemporaryPostStore.GetExpiredPosts |  Avg| 13ms| 17ms | 4ms | 30.052
| |  P99| 93ms| 96ms | 3ms | 3.226
| ThreadStore.Get |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 200ms| 163ms | -37ms | -18.454
| ThreadStore.GetMembershipForUser |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 173ms| 149ms | -24ms | -13.892
| ThreadStore.GetTeamsUnreadForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 201ms| 191ms | -10ms | -4.970
| ThreadStore.GetThreadFollowers |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 155ms| 142ms | -13ms | -8.380
| ThreadStore.GetThreadForUser |  Avg| 23ms| 22ms | -1ms | -4.428
| |  P99| 236ms| 228ms | -8ms | -3.396
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 21ms| 20ms | -1ms | -4.805
| |  P99| 193ms| 180ms | -13ms | -6.730
| ThreadStore.GetThreadsForUser |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 197ms| 184ms | -13ms | -6.609
| ThreadStore.GetTotalThreads |  Avg| 11ms| 10ms | -1ms | -9.341
| |  P99| 99ms| 98ms | -1ms | -1.007
| ThreadStore.GetTotalUnreadMentions |  Avg| 12ms| 11ms | -1ms | -8.392
| |  P99| 138ms| 108ms | -30ms | -21.666
| ThreadStore.GetTotalUnreadThreads |  Avg| 11ms| 10ms | -1ms | -9.254
| |  P99| 99ms| 97ms | -2ms | -2.022
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 104ms| 98ms | -6ms | -5.749
| ThreadStore.MaintainMembership |  Avg| 19ms| 20ms | 1ms | 5.160
| |  P99| 228ms| 229ms | 1ms | 0.439
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 91ms | -3ms | -3.197
| ThreadStore.MarkAllAsReadByTeam |  Avg| 7ms| 13ms | 6ms | 90.423
| |  P99| 24ms| 48ms | 24ms | 98.968
| ThreadStore.MarkAsRead |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 92ms | -1ms | -1.078
| ThreadStore.UpdateMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.106
| TokenStore.Cleanup |  Avg| 17ms| 27ms | 10ms | 60.535
| |  P99| 48ms| 241ms | 193ms | 397.941
| UserAccessTokenStore.GetByToken |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 92ms| 88ms | -4ms | -4.360
| UserStore.AnalyticsActiveCount |  Avg| 37ms| 0s | -37ms | -99.709
| |  P99| 50ms| 0s | -50ms | -100.503
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 25ms| 0s | -25ms | -101.784
| |  P99| 25ms| 0s | -25ms | -100.604
| UserStore.AutocompleteUsersInChannel |  Avg| 78ms| 77ms | -1ms | -1.290
| |  P99| 384ms| 388ms | 4ms | 1.042
| UserStore.Count |  Avg| 26ms| 25ms | -1ms | -3.921
| |  P99| 179ms| 171ms | -8ms | -4.465
| UserStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 145ms| 134ms | -11ms | -7.586
| UserStore.GetAllProfiles |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 85ms | -3ms | -3.417
| UserStore.GetAllProfilesInChannel |  Avg| 409ms| 406ms | -3ms | -0.734
| |  P99| 2.213s| 2.206s | -7ms | -0.316
| UserStore.GetByUsername |  Avg| 14ms| 17ms | 3ms | 20.986
| |  P99| 209ms| 210ms | 1ms | 0.479
| UserStore.GetForLogin |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 95ms | -3ms | -3.068
| UserStore.GetMany |  Avg| 16ms| 12ms | -4ms | -25.369
| |  P99| 166ms| 161ms | -5ms | -3.012
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 5ms| 0s | -5ms | -107.613
| |  P99| 5ms| 0s | -5ms | -100.922
| UserStore.GetProfileByIds |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 182ms| 172ms | -10ms | -5.506
| UserStore.GetProfilesByUsernames |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 180ms| 168ms | -12ms | -6.652
| UserStore.GetProfilesInChannel |  Avg| 17ms| 8ms | -9ms | -51.454
| |  P99| 413ms| 77ms | -336ms | -81.451
| UserStore.GetProfilesNotInChannel |  Avg| 13ms| 16ms | 3ms | 23.199
| |  P99| 85ms| 192ms | 107ms | 125.149
| UserStore.GetUnreadCount |  Avg| 13ms| 12ms | -1ms | -7.839
| |  P99| 160ms| 137ms | -23ms | -14.412
| UserStore.IsEmpty |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 57ms| 49ms | -8ms | -14.058
| UserStore.Save |  Avg| 174ms| 172ms | -2ms | -1.151
| |  P99| 546ms| 580ms | 34ms | 6.224
| UserStore.Search |  Avg| 51ms| 52ms | 1ms | 1.963
| |  P99| 241ms| 241ms | 0s | 0.000
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 78ms| 79ms | 1ms | 1.289
| UserStore.Update |  Avg| 29ms| 23ms | -6ms | -21.039
| |  P99| 236ms| 223ms | -13ms | -5.506
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 88ms | 1ms | 1.152
| UserStore.UpdateLastLogin |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 78ms | 1ms | 1.293
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 74ms| 78ms | 4ms | 5.402
| UserTermsOfServiceStore.GetByUser |  Avg| 10ms| 9ms | -1ms | -10.404
| |  P99| 100ms| 96ms | -4ms | -4.001
| WebhookStore.GetOutgoingByTeam |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 209ms| 201ms | -8ms | -3.832
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 535ms| 535ms | 0s | 0.000
| | P99| 2.861s| 2.488s | -373ms | -13.038
| addTeamMember | Avg| 1.392s| 1.357s | -35ms | -2.514
| | P99| 8.559s| 8.493s | -66ms | -0.771
| autocompleteChannelsForTeamForSearch | Avg| 73ms| 104ms | 31ms | 42.208
| | P99| 383ms| 751ms | 368ms | 96.083
| autocompleteUsers | Avg| 73ms| 72ms | -1ms | -1.375
| | P99| 400ms| 401ms | 1ms | 0.250
| channelMemberCountsByGroup | Avg| 3ms| 0s | -3ms | -95.824
| | P99| 5ms| 0s | -5ms | -100.966
| createCategoryForTeamForUser | Avg| 63ms| 19ms | -44ms | -69.716
| | P99| 473ms| 97ms | -376ms | -79.576
| createChannel | Avg| 688ms| 513ms | -175ms | -25.445
| | P99| 4.275s| 2.354s | -1.921s | -44.934
| createChannelBookmark | Avg| 110ms| 71ms | -39ms | -35.529
| | P99| 2.155s| 245ms | -1.91s | -88.632
| createDirectChannel | Avg| 584ms| 559ms | -25ms | -4.280
| | P99| 2.5s| 2.473s | -27ms | -1.080
| createEmoji | Avg| 7ms| 0s | -7ms | -98.204
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 962ms| 940ms | -22ms | -2.287
| | P99| 4.723s| 4.593s | -130ms | -2.753
| createPost | Avg| 729ms| 710ms | -19ms | -2.605
| | P99| 4.594s| 4.465s | -129ms | -2.808
| createSchedulePost | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 172ms| 155ms | -17ms | -9.884
| createUser | Avg| 414ms| 408ms | -6ms | -1.451
| | P99| 2.29s| 2.303s | 13ms | 0.568
| deleteChannelBookmark | Avg| 30ms| 163ms | 133ms | 447.894
| | P99| 50ms| 249ms | 199ms | 400.974
| deleteDraft | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 217ms| 211ms | -6ms | -2.762
| deletePost | Avg| 125ms| 64ms | -61ms | -48.941
| | P99| 2.08s| 444ms | -1.636s | -78.649
| deleteScheduledPost | Avg| 6ms| 0s | -6ms | -97.650
| | P99| 10ms| 0s | -10ms | -100.503
| followThreadByUser | Avg| 69ms| 85ms | 16ms | 23.106
| | P99| 685ms| 1.915s | 1.23s | 179.574
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getAllTeams | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 166ms| 154ms | -12ms | -7.219
| getCategoriesForTeamForUser | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 226ms| 217ms | -9ms | -3.985
| getChannel | Avg| 32ms| 24ms | -8ms | -25.340
| | P99| 396ms| 231ms | -165ms | -41.706
| getChannelMember | Avg| 21ms| 20ms | -1ms | -4.716
| | P99| 241ms| 239ms | -2ms | -0.831
| getChannelMembers | Avg| 16ms| 31ms | 15ms | 92.626
| | P99| 95ms| 99ms | 4ms | 4.233
| getChannelMembersForTeamForUser | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 191ms| 182ms | -9ms | -4.718
| getChannelMembersForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 114ms| 110ms | -4ms | -3.522
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 153ms| 146ms | -7ms | -4.574
| getChannelUnread | Avg| 18ms| 16ms | -2ms | -11.214
| | P99| 218ms| 198ms | -20ms | -9.159
| getChannelsForTeamForUser | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 201ms| 191ms | -10ms | -4.971
| getChannelsForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 104ms| 98ms | -6ms | -5.746
| getClientConfig | Avg| 20ms| 19ms | -1ms | -4.992
| | P99| 232ms| 232ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getConfig | Avg| 34ms| 0s | -34ms | -100.277
| | P99| 50ms| 0s | -50ms | -100.503
| getDrafts | Avg| 18ms| 16ms | -2ms | -11.233
| | P99| 208ms| 189ms | -19ms | -9.135
| getFilePreview | Avg| 75ms| 76ms | 1ms | 1.335
| | P99| 420ms| 414ms | -6ms | -1.427
| getFileThumbnail | Avg| 69ms| 70ms | 1ms | 1.442
| | P99| 374ms| 362ms | -12ms | -3.206
| getFilteredUsersStats | Avg| 17ms| 0s | -17ms | -99.611
| | P99| 25ms| 0s | -25ms | -100.604
| getJobsByType | Avg| 15ms| 0s | -15ms | -100.915
| | P99| 93ms| 0s | -93ms | -99.466
| getPostThread | Avg| 79ms| 79ms | 0s | 0.000
| | P99| 802ms| 762ms | -40ms | -4.988
| getPostsForChannel | Avg| 188ms| 186ms | -2ms | -1.062
| | P99| 2.374s| 2.317s | -57ms | -2.401
| getPostsForChannelAroundLastUnread | Avg| 57ms| 58ms | 1ms | 1.756
| | P99| 494ms| 526ms | 32ms | 6.474
| getPreferences | Avg| 12ms| 11ms | -1ms | -8.388
| | P99| 143ms| 123ms | -20ms | -14.006
| getPrevTrialLicense | Avg| 5ms| 0s | -5ms | -91.331
| | P99| 25ms| 0s | -25ms | -101.833
| getProfileImage | Avg| 74ms| 72ms | -2ms | -2.716
| | P99| 474ms| 473ms | -1ms | -0.211
| getPropertyFields | Avg| 5ms| 0s | -5ms | -94.669
| | P99| 10ms| 0s | -10ms | -101.523
| getPublicChannelsForTeam | Avg| 35ms| 34ms | -1ms | -2.862
| | P99| 248ms| 230ms | -18ms | -7.269
| getRolesByNames | Avg| 8ms| 0s | -8ms | -104.731
| | P99| 10ms| 0s | -10ms | -100.503
| getServerLimits | Avg| 25ms| 0s | -25ms | -101.546
| | P99| 50ms| 0s | -50ms | -101.010
| getTeamMember | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 137ms| 151ms | 14ms | 10.246
| getTeamMembersForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 145ms| 129ms | -16ms | -11.055
| getTeamScheduledPosts | Avg| 19ms| 18ms | -1ms | -5.233
| | P99| 217ms| 210ms | -7ms | -3.223
| getTeamStats | Avg| 91ms| 76ms | -15ms | -16.419
| | P99| 428ms| 242ms | -186ms | -43.507
| getTeamsForUser | Avg| 11ms| 10ms | -1ms | -8.914
| | P99| 132ms| 100ms | -32ms | -24.291
| getTeamsUnreadForUser | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 238ms| 234ms | -4ms | -1.683
| getThreadsForUser | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 213ms| 203ms | -10ms | -4.704
| getUser | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 248ms| 245ms | -3ms | -1.208
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 93ms| 88ms | -5ms | -5.357
| getUsers | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 243ms| 241ms | -2ms | -0.823
| getUsersByGroupChannelIds | Avg| 5ms| 0s | -5ms | -102.030
| | P99| 5ms| 0s | -5ms | -100.922
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 52ms| 51ms | -1ms | -1.918
| getUsersByNames | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 194ms| 186ms | -8ms | -4.126
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 226ms| 223ms | -3ms | -1.326
| listCPAValues | Avg| 31ms| 29ms | -2ms | -6.504
| | P99| 315ms| 275ms | -40ms | -12.708
| listChannelBookmarksForChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 175ms| 164ms | -11ms | -6.300
| login | Avg| 162ms| 161ms | -1ms | -0.618
| | P99| 975ms| 975ms | 0s | 0.000
| logout | Avg| 142ms| 127ms | -15ms | -10.581
| | P99| 1.51s| 840ms | -670ms | -44.363
| patchPost | Avg| 145ms| 118ms | -27ms | -18.684
| | P99| 1.555s| 888ms | -667ms | -42.896
| removeUserCustomStatus | Avg| 356ms| 352ms | -4ms | -1.124
| | P99| 1.125s| 1.969s | 844ms | 75.027
| root | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 223ms| 219ms | -4ms | -1.796
| saveReaction | Avg| 70ms| 67ms | -3ms | -4.303
| | P99| 467ms| 434ms | -33ms | -7.072
| searchAllChannels | Avg| 56ms| 55ms | -1ms | -1.798
| | P99| 248ms| 271ms | 23ms | 9.279
| searchGroupChannels | Avg| 19ms| 18ms | -1ms | -5.300
| | P99| 207ms| 201ms | -6ms | -2.898
| searchPostsInTeam | Avg| 337ms| 345ms | 8ms | 2.374
| | P99| 3.993s| 4.098s | 105ms | 2.630
| searchUsers | Avg| 53ms| 54ms | 1ms | 1.883
| | P99| 244ms| 245ms | 1ms | 0.410
| setPostReminder | Avg| 130ms| 96ms | -34ms | -26.064
| | P99| 930ms| 468ms | -462ms | -49.677
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 65ms| 66ms | 1ms | 1.549
| | P99| 467ms| 451ms | -16ms | -3.427
| updateCategoriesForTeamForUser | Avg| 168ms| 170ms | 2ms | 1.193
| | P99| 1.09s| 2.117s | 1.027s | 94.237
| updateChannelBookmark | Avg| 76ms| 33ms | -43ms | -56.873
| | P99| 935ms| 98ms | -837ms | -89.523
| updateChannelBookmarkSortOrder | Avg| 65ms| 26ms | -39ms | -59.706
| | P99| 244ms| 99ms | -145ms | -59.426
| updatePreferences | Avg| 38ms| 40ms | 2ms | 5.326
| | P99| 371ms| 355ms | -16ms | -4.310
| updateReadStateAllThreadsByUser | Avg| 7ms| 13ms | 6ms | 89.057
| | P99| 49ms| 48ms | -1ms | -2.051
| updateReadStateThreadByUser | Avg| 155ms| 153ms | -2ms | -1.289
| | P99| 1.355s| 1.125s | -230ms | -16.972
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 541ms| 546ms | 5ms | 0.925
| | P99| 2.22s| 2.222s | 2ms | 0.090
| upsertDraft | Avg| 18ms| 17ms | -1ms | -5.596
| | P99| 209ms| 203ms | -6ms | -2.868
| viewChannel | Avg| 71ms| 70ms | -1ms | -1.403
| | P99| 744ms| 713ms | -31ms | -4.168
