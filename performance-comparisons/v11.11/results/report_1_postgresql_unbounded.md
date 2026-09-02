### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 3ms | 23ms | 20ms | 623.46
| UserStore.AnalyticsGetInactiveUsersCount | avg | 2ms | 10ms | 8ms | 503.28
| CommandWebhookStore.Cleanup | avg | 8ms | 31ms | 23ms | 290.50
| TokenStore.Cleanup | avg | 9ms | 25ms | 16ms | 187.11
| JobStore.GetAllByTypePage | avg | 15ms | 29ms | 14ms | 95.30
| ProductNoticesStore.ClearOldNotices | avg | 46ms | 87ms | 41ms | 89.09
| PostPersistentNotificationStore.Get | avg | 11ms | 19ms | 8ms | 74.05
| PreferenceStore.DeleteCategoryAndName | avg | 14ms | 24ms | 10ms | 71.97
| ChannelBookmarkStore.Get | avg | 10ms | 15ms | 5ms | 49.68
| ChannelStore.UpdateSidebarCategories | avg | 83ms | 119ms | 36ms | 43.63
| ChannelStore.GetMany | avg | 29ms | 41ms | 12ms | 42.07
| PostPersistentNotificationStore.DeleteExpired | avg | 10ms | 14ms | 4ms | 40.92
| PropertyGroupStore.Get | avg | 11ms | 15ms | 4ms | 34.90
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 20ms | 27ms | 7ms | 34.22
| JobStore.UpdateStatus | avg | 12ms | 16ms | 4ms | 32.87
| ChannelBookmarkStore.Delete | avg | 13ms | 17ms | 4ms | 31.72
| PropertyFieldStore.SearchPropertyFields | avg | 10ms | 13ms | 3ms | 30.59
| UserStore.GetProfilesNotInChannel | avg | 17ms | 22ms | 5ms | 30.15
| JobStore.UpdateStatusOptimistically | avg | 12ms | 15ms | 3ms | 25.93
| JobStore.GetNewestJobByStatusesAndType | avg | 8ms | 10ms | 2ms | 24.99
| StatusStore.UpdateExpiredDNDStatuses | avg | 10ms | 12ms | 2ms | 19.28
| ChannelStore.GetMembers | avg | 11ms | 13ms | 2ms | 17.65
| TeamStore.GetActiveMemberCount | avg | 73ms | 84ms | 11ms | 15.14
| PostStore.SearchPostsForUser | avg | 288ms | 302ms | 14ms | 4.86
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 5ms | 98ms | 93ms | 1878.79
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 49ms | 44ms | 888.51
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 248ms | 198ms | 397.99
| JobStore.GetAllByTypePage | p99 | 49ms | 239ms | 190ms | 387.20
| PreferenceStore.DeleteCategoryAndName | p99 | 49ms | 222ms | 173ms | 355.48
| ChannelStore.GetMembers | p99 | 25ms | 95ms | 70ms | 283.40
| UserStore.GetProfilesNotInChannel | p99 | 95ms | 211ms | 116ms | 121.94
| ChannelBookmarkStore.Get | p99 | 90ms | 189ms | 99ms | 110.30
| CommandWebhookStore.Cleanup | p99 | 48ms | 97ms | 49ms | 101.03
| ChannelBookmarkStore.Delete | p99 | 48ms | 95ms | 47ms | 96.91
| ThreadStore.MarkAllAsReadByTeam | p99 | 49ms | 96ms | 47ms | 96.66
| PropertyFieldStore.SearchPropertyFields | p99 | 111ms | 216ms | 105ms | 94.75
| JobStore.UpdateStatus | p99 | 97ms | 186ms | 89ms | 91.29
| JobStore.GetNewestJobByStatusesAndType | p99 | 80ms | 153ms | 73ms | 90.97
| TeamStore.GetActiveMemberCount | p99 | 242ms | 435ms | 193ms | 79.87
| PostPersistentNotificationStore.Get | p99 | 90ms | 154ms | 64ms | 71.37
| PostPersistentNotificationStore.DeleteExpired | p99 | 90ms | 154ms | 64ms | 71.37
| JobStore.UpdateOptimistically | p99 | 68ms | 99ms | 31ms | 45.26
| JobStore.Save | p99 | 80ms | 96ms | 16ms | 20.00
| ChannelStore.GetMany | p99 | 335ms | 400ms | 65ms | 19.40
| ChannelStore.UpdateSidebarCategories | p99 | 743ms | 862ms | 119ms | 16.03
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 202ms | 222ms | 20ms | 9.90
| ScheduledPostStore.CreateScheduledPost | p99 | 85ms | 93ms | 8ms | 9.38
| TeamStore.GetTotalMemberCount | p99 | 403ms | 435ms | 32ms | 7.95
| FileInfoStore.SetContent | p99 | 222ms | 234ms | 12ms | 5.40
| TokenStore.Cleanup | p99 | 48ms | 50ms | 2ms | 4.12
| StatusStore.SaveOrUpdateMany | p99 | 213ms | 221ms | 8ms | 3.76
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PropertyValueStore.SearchPropertyValues | avg | 16ms | 0s | -16ms | -101.40
| ChannelStore.GetMemberCountsByGroup | avg | 18ms | 0s | -18ms | -98.65
| EmojiStore.Search | avg | 3ms | 0s | -3ms | -96.38
| LicenseStore.GetAll | avg | 17ms | 2ms | -15ms | -88.00
| PostStore.AnalyticsPostCountByTeam | avg | 9ms | 1ms | -8ms | -84.79
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 19ms | 3ms | -16ms | -82.80
| EmojiStore.GetMultipleByName | avg | 24ms | 4ms | -20ms | -82.07
| RoleStore.ChannelHigherScopedPermissions | avg | 37ms | 13ms | -24ms | -64.73
| ProductNoticesStore.GetViews | avg | 15ms | 6ms | -9ms | -60.04
| BotStore.Get | avg | 14ms | 6ms | -8ms | -56.28
| UserStore.GetProfilesInChannel | avg | 22ms | 10ms | -12ms | -53.94
| RoleStore.GetByNames | avg | 47ms | 26ms | -21ms | -44.69
| ChannelStore.CreateSidebarCategory | avg | 86ms | 49ms | -37ms | -43.24
| UserAccessTokenStore.GetByToken | avg | 17ms | 10ms | -7ms | -40.81
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 7ms | 4ms | -3ms | -40.78
| ChannelBookmarkStore.Save | avg | 58ms | 35ms | -23ms | -39.41
| FileInfoStore.GetForPost | avg | 11ms | 7ms | -4ms | -37.95
| PostStore.Delete | avg | 86ms | 58ms | -28ms | -32.69
| LinkMetadataStore.Save | avg | 16ms | 11ms | -5ms | -31.94
| UserStore.GetMany | avg | 16ms | 11ms | -5ms | -30.32
| PostAcknowledgementStore.GetForPost | avg | 14ms | 10ms | -4ms | -28.66
| TeamStore.Get | avg | 15ms | 11ms | -4ms | -27.55
| PostStore.SetPostReminder | avg | 48ms | 35ms | -13ms | -27.11
| PostStore.GetSingle | avg | 15ms | 11ms | -4ms | -26.74
| ScheduledPostStore.GetPendingScheduledPosts | avg | 19ms | 14ms | -5ms | -26.02
| ChannelStore.AnalyticsCountAll | avg | 39ms | 29ms | -10ms | -25.91
| TemporaryPostStore.GetExpiredPosts | avg | 24ms | 18ms | -6ms | -25.32
| UserStore.Update | avg | 33ms | 25ms | -8ms | -24.40
| ChannelStore.GetPinnedPostCount | avg | 17ms | 13ms | -4ms | -24.08
| PostStore.AnalyticsPostCount | avg | 491ms | 373ms | -118ms | -24.02
| PreferenceStore.GetAll | avg | 13ms | 10ms | -3ms | -23.88
| UserStore.AnalyticsActiveCount | avg | 34ms | 26ms | -8ms | -23.49
| ThreadStore.Get | avg | 17ms | 13ms | -4ms | -22.86
| PostPersistentNotificationStore.GetSingle | avg | 13ms | 10ms | -3ms | -22.79
| StatusStore.GetByIds | avg | 23ms | 18ms | -5ms | -22.03
| PostPriorityStore.GetForPostWithContext | avg | 14ms | 11ms | -3ms | -21.34
| PostAcknowledgementStore.GetForPosts | avg | 24ms | 19ms | -5ms | -21.14
| ChannelStore.AutocompleteInTeamForSearch | avg | 82ms | 65ms | -17ms | -20.81
| ThreadStore.GetThreadFollowers | avg | 15ms | 12ms | -3ms | -20.65
| SessionStore.Remove | avg | 15ms | 12ms | -3ms | -20.53
| UserStore.GetUnreadCount | avg | 15ms | 12ms | -3ms | -20.32
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 15ms | 12ms | -3ms | -20.27
| PostPriorityStore.GetForPosts | avg | 25ms | 20ms | -5ms | -20.24
| ChannelStore.Get | avg | 30ms | 24ms | -6ms | -20.22
| PreferenceStore.Get | avg | 15ms | 12ms | -3ms | -20.19
| EmojiStore.GetByName | avg | 15ms | 12ms | -3ms | -19.93
| LinkMetadataStore.Get | avg | 15ms | 12ms | -3ms | -19.63
| DraftStore.Get | avg | 21ms | 17ms | -4ms | -19.45
| ThreadStore.GetThreadsForUser | avg | 21ms | 17ms | -4ms | -19.43
| PostStore.GetPostsByThread | avg | 21ms | 17ms | -4ms | -19.23
| GroupStore.GetGroups | avg | 16ms | 13ms | -3ms | -18.96
| UserTermsOfServiceStore.GetByUser | avg | 11ms | 9ms | -2ms | -18.93
| ThreadStore.GetMembershipForUser | avg | 16ms | 13ms | -3ms | -18.77
| ThreadStore.GetThreadForUser | avg | 27ms | 22ms | -5ms | -18.26
| UserStore.GetProfileByIds | avg | 17ms | 14ms | -3ms | -17.91
| PostStore.GetPostReminderMetadata | avg | 17ms | 14ms | -3ms | -17.86
| PostStore.GetEtag | avg | 17ms | 14ms | -3ms | -17.75
| ClusterDiscoveryStore.SetLastPingAt | avg | 17ms | 14ms | -3ms | -17.60
| ChannelStore.GetForPost | avg | 23ms | 19ms | -4ms | -17.44
| TeamStore.GetAllPage | avg | 12ms | 10ms | -2ms | -16.98
| ThreadStore.GetTeamsUnreadForUser | avg | 18ms | 15ms | -3ms | -16.96
| ThreadStore.GetTotalUnreadThreads | avg | 12ms | 10ms | -2ms | -16.73
| TeamStore.GetTeamsByUserId | avg | 12ms | 10ms | -2ms | -16.66
| ThreadStore.GetTotalThreads | avg | 12ms | 10ms | -2ms | -16.58
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 12ms | 10ms | -2ms | -16.53
| ChannelStore.GetMembersForUser | avg | 18ms | 15ms | -3ms | -16.50
| PostStore.Get | avg | 37ms | 31ms | -6ms | -16.32
| ChannelStore.GetChannels | avg | 19ms | 16ms | -3ms | -16.04
| PostStore.GetPostsBefore | avg | 19ms | 16ms | -3ms | -15.92
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 32ms | 27ms | -5ms | -15.86
| ChannelStore.GetMembersForUserWithPagination | avg | 13ms | 11ms | -2ms | -15.72
| ChannelStore.GetChannelUnread | avg | 19ms | 16ms | -3ms | -15.57
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 13ms | 11ms | -2ms | -15.53
| DraftStore.GetDraftsForUser | avg | 20ms | 17ms | -3ms | -15.11
| ThreadStore.GetTotalUnreadMentions | avg | 13ms | 11ms | -2ms | -15.10
| UserStore.Get | avg | 14ms | 12ms | -2ms | -14.72
| ChannelStore.SaveMember | avg | 83ms | 71ms | -12ms | -14.51
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 14ms | 12ms | -2ms | -14.42
| ReactionStore.GetForPost | avg | 14ms | 12ms | -2ms | -14.34
| StatusStore.Get | avg | 14ms | 12ms | -2ms | -14.27
| WebhookStore.GetOutgoingByTeam | avg | 21ms | 18ms | -3ms | -14.12
| JobStore.GetCountByStatusAndType | avg | 14ms | 12ms | -2ms | -13.98
| ChannelStore.SearchGroupChannels | avg | 21ms | 18ms | -3ms | -13.96
| ChannelStore.GetByName | avg | 15ms | 13ms | -2ms | -13.68
| ChannelStore.GetGuestCount | avg | 15ms | 13ms | -2ms | -13.46
| ChannelStore.GetFileCount | avg | 16ms | 14ms | -2ms | -12.72
| FileInfoStore.Get | avg | 16ms | 14ms | -2ms | -12.68
| ChannelStore.GetBoardChannel | avg | 16ms | 14ms | -2ms | -12.62
| ThreadStore.MaintainMembership | avg | 24ms | 21ms | -3ms | -12.55
| ChannelStore.CreateInitialSidebarCategories | avg | 40ms | 35ms | -5ms | -12.47
| ThreadStore.GetThreadUnreadReplyCount | avg | 24ms | 21ms | -3ms | -12.38
| ChannelStore.GetAllChannelMembersForUser | avg | 16ms | 14ms | -2ms | -12.28
| UserStore.GetProfilesByUsernames | avg | 17ms | 15ms | -2ms | -11.60
| ProductNoticesStore.View | avg | 115ms | 102ms | -13ms | -11.33
| JobStore.GetAllByStatus | avg | 19ms | 17ms | -2ms | -10.48
| ChannelStore.GetSidebarCategory | avg | 30ms | 27ms | -3ms | -9.96
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 20ms | 18ms | -2ms | -9.79
| SessionStore.Get | avg | 21ms | 19ms | -2ms | -9.51
| PreferenceStore.Save | avg | 32ms | 29ms | -3ms | -9.46
| ChannelStore.Save | avg | 54ms | 49ms | -5ms | -9.33
| FileInfoStore.AttachToPost | avg | 22ms | 20ms | -2ms | -9.24
| TeamStore.SaveMember | avg | 45ms | 41ms | -4ms | -8.91
| PostStore.GetPostsSince | avg | 34ms | 31ms | -3ms | -8.75
| ChannelStore.Autocomplete | avg | 59ms | 54ms | -5ms | -8.47
| ChannelStore.GetPublicChannelsForTeam | avg | 36ms | 33ms | -3ms | -8.34
| ChannelStore.CreateDirectChannel | avg | 102ms | 94ms | -8ms | -7.83
| UserStore.Count | avg | 26ms | 24ms | -2ms | -7.76
| ChannelStore.GetMemberCount | avg | 40ms | 37ms | -3ms | -7.49
| PostStore.Save | avg | 41ms | 38ms | -3ms | -7.24
| UserStore.AutocompleteUsersInChannel | avg | 86ms | 80ms | -6ms | -6.98
| ChannelStore.GetMemberForPost | avg | 44ms | 41ms | -3ms | -6.86
| ChannelStore.GetTeamChannels | avg | 53ms | 50ms | -3ms | -5.68
| UserStore.Search | avg | 60ms | 57ms | -3ms | -4.97
| UserStore.GetAllProfilesInChannel | avg | 422ms | 403ms | -19ms | -4.51
| UserStore.Save | avg | 168ms | 162ms | -6ms | -3.57
| TeamStore.GetTotalMemberCount | avg | 78ms | 76ms | -2ms | -2.55
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 10ms | 0s | -10ms | -101.01
| PropertyValueStore.SearchPropertyValues | p99 | 216ms | 0s | -216ms | -99.92
| ChannelStore.GetMemberCountsByGroup | p99 | 206ms | 0s | -206ms | -99.76
| LicenseStore.GetAll | p99 | 49ms | 5ms | -44ms | -89.34
| BotStore.Get | p99 | 410ms | 47ms | -363ms | -88.54
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 25ms | 5ms | -20ms | -80.46
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 195ms | 40ms | -155ms | -79.69
| UserStore.GetProfilesInChannel | p99 | 227ms | 48ms | -179ms | -79.03
| EmojiStore.GetMultipleByName | p99 | 95ms | 23ms | -72ms | -75.59
| ProductNoticesStore.GetViews | p99 | 25ms | 10ms | -15ms | -60.35
| PostStore.AnalyticsPostCount | p99 | 2.455s | 980ms | -1.475s | -60.08
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 232ms | 93ms | -139ms | -60.04
| TemporaryPostStore.GetExpiredPosts | p99 | 227ms | 96ms | -131ms | -57.58
| UserAccessTokenStore.GetByToken | p99 | 191ms | 83ms | -108ms | -56.62
| ChannelStore.GetSidebarCategory | p99 | 490ms | 239ms | -251ms | -51.21
| PostStore.AnalyticsPostCountByTeam | p99 | 10ms | 5ms | -5ms | -50.24
| ChannelStore.CreateSidebarCategory | p99 | 486ms | 243ms | -243ms | -49.97
| ChannelBookmarkStore.UpdateSortOrder | p99 | 48ms | 24ms | -24ms | -49.74
| UserStore.GetMany | p99 | 165ms | 87ms | -78ms | -47.41
| PostStore.GetPostReminders | p99 | 82ms | 45ms | -37ms | -45.40
| ChannelBookmarkStore.Save | p99 | 405ms | 230ms | -175ms | -43.21
| ChannelStore.GetTeamChannels | p99 | 403ms | 230ms | -173ms | -42.98
| RoleStore.ChannelHigherScopedPermissions | p99 | 248ms | 147ms | -101ms | -40.75
| PropertyGroupStore.Get | p99 | 160ms | 96ms | -64ms | -40.08
| TeamStore.GetAllPage | p99 | 169ms | 103ms | -66ms | -39.07
| JobStore.UpdateStatusOptimistically | p99 | 160ms | 98ms | -62ms | -38.74
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 159ms | 101ms | -58ms | -36.55
| ChannelStore.Autocomplete | p99 | 388ms | 247ms | -141ms | -36.34
| ThreadStore.GetTotalThreads | p99 | 163ms | 105ms | -58ms | -35.53
| UserTermsOfServiceStore.GetByUser | p99 | 155ms | 101ms | -54ms | -34.92
| PostPriorityStore.GetForPosts | p99 | 380ms | 248ms | -132ms | -34.73
| PostStore.Get | p99 | 390ms | 256ms | -134ms | -34.33
| PostAcknowledgementStore.GetForPosts | p99 | 374ms | 247ms | -127ms | -33.98
| SessionStore.Remove | p99 | 142ms | 94ms | -48ms | -33.81
| JobStore.GetCountByStatusAndType | p99 | 147ms | 98ms | -49ms | -33.28
| PostPersistentNotificationStore.GetSingle | p99 | 211ms | 141ms | -70ms | -33.21
| ChannelStore.Get | p99 | 355ms | 238ms | -117ms | -33.00
| ThreadStore.GetTotalUnreadThreads | p99 | 159ms | 107ms | -52ms | -32.74
| PreferenceStore.GetAll | p99 | 177ms | 120ms | -57ms | -32.22
| TeamStore.GetTeamsForUser | p99 | 147ms | 100ms | -47ms | -31.95
| TeamStore.GetTeamsByUserId | p99 | 169ms | 117ms | -52ms | -30.81
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 177ms | 123ms | -54ms | -30.51
| ThreadStore.GetThreadForUser | p99 | 338ms | 238ms | -100ms | -29.60
| RoleStore.GetByNames | p99 | 246ms | 176ms | -70ms | -28.48
| PostPriorityStore.GetForPostWithContext | p99 | 216ms | 155ms | -61ms | -28.19
| PostAcknowledgementStore.GetForPost | p99 | 218ms | 157ms | -61ms | -28.05
| ChannelStore.GetByName | p99 | 173ms | 126ms | -47ms | -27.10
| ReactionStore.GetForPost | p99 | 207ms | 151ms | -56ms | -27.05
| TeamStore.Get | p99 | 218ms | 160ms | -58ms | -26.60
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 128ms | 94ms | -34ms | -26.49
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 195ms | 145ms | -50ms | -25.65
| PostStore.GetSingle | p99 | 219ms | 163ms | -56ms | -25.53
| ThreadStore.GetTotalUnreadMentions | p99 | 187ms | 140ms | -47ms | -25.09
| PostStore.GetPostsByThread | p99 | 228ms | 171ms | -57ms | -25.05
| ChannelStore.SaveMember | p99 | 831ms | 627ms | -204ms | -24.55
| LinkMetadataStore.Get | p99 | 221ms | 167ms | -54ms | -24.43
| EmojiStore.GetByName | p99 | 208ms | 158ms | -50ms | -24.07
| ChannelStore.GetFileCount | p99 | 192ms | 146ms | -46ms | -23.91
| UserStore.GetUnreadCount | p99 | 212ms | 162ms | -50ms | -23.57
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 175ms | 134ms | -41ms | -23.42
| ChannelStore.GetAllChannelMembersForUser | p99 | 186ms | 143ms | -43ms | -23.18
| ChannelStore.GetPinnedPostCount | p99 | 226ms | 174ms | -52ms | -23.05
| FileInfoStore.Save | p99 | 165ms | 127ms | -38ms | -23.01
| ChannelStore.AutocompleteInTeamForSearch | p99 | 557ms | 430ms | -127ms | -22.80
| ChannelStore.GetGuestCount | p99 | 198ms | 154ms | -44ms | -22.18
| ClusterDiscoveryStore.SetLastPingAt | p99 | 168ms | 131ms | -37ms | -22.06
| StatusStore.Get | p99 | 200ms | 156ms | -44ms | -21.99
| ChannelStore.GetMembersForUserWithPagination | p99 | 166ms | 130ms | -36ms | -21.73
| GroupStore.GetGroups | p99 | 215ms | 169ms | -46ms | -21.37
| UserStore.Save | p99 | 653ms | 517ms | -136ms | -20.82
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 211ms | 167ms | -44ms | -20.82
| SessionStore.GetLRUSessions | p99 | 118ms | 94ms | -24ms | -20.30
| ThreadStore.GetThreadFollowers | p99 | 213ms | 170ms | -43ms | -20.15
| ChannelStore.GetChannelsByUser | p99 | 124ms | 99ms | -25ms | -20.12
| UserStore.Get | p99 | 189ms | 151ms | -38ms | -20.08
| PreferenceStore.Get | p99 | 204ms | 163ms | -41ms | -20.08
| ChannelStore.SearchGroupChannels | p99 | 237ms | 190ms | -47ms | -19.87
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 409ms | 329ms | -80ms | -19.54
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 121ms | 98ms | -23ms | -19.04
| UserStore.IsEmpty | p99 | 69ms | 56ms | -13ms | -18.92
| UserStore.GetForLogin | p99 | 122ms | 99ms | -23ms | -18.84
| ThreadStore.GetMembershipForUser | p99 | 219ms | 180ms | -39ms | -17.82
| ChannelStore.GetBoardChannel | p99 | 207ms | 173ms | -34ms | -16.40
| DraftStore.Upsert | p99 | 136ms | 114ms | -22ms | -16.19
| StatusStore.SaveOrUpdate | p99 | 118ms | 99ms | -19ms | -16.08
| UserStore.GetProfileByIds | p99 | 214ms | 180ms | -34ms | -15.89
| ChannelStore.GetMembersForUser | p99 | 222ms | 187ms | -35ms | -15.79
| ThreadStore.GetThreadUnreadReplyCount | p99 | 230ms | 194ms | -36ms | -15.67
| PostStore.GetEtag | p99 | 215ms | 182ms | -33ms | -15.33
| FileInfoStore.GetForPost | p99 | 100ms | 85ms | -15ms | -15.06
| ChannelStore.GetChannelUnread | p99 | 227ms | 194ms | -33ms | -14.55
| UserStore.GetProfilesByUsernames | p99 | 211ms | 182ms | -29ms | -13.74
| DraftStore.GetDraftsForUser | p99 | 238ms | 206ms | -32ms | -13.46
| PostStore.GetPostsBefore | p99 | 220ms | 191ms | -29ms | -13.18
| TeamStore.SaveMember | p99 | 283ms | 246ms | -37ms | -13.09
| FileInfoStore.Get | p99 | 207ms | 180ms | -27ms | -13.05
| ThreadStore.GetThreadsForUser | p99 | 230ms | 200ms | -30ms | -13.03
| JobStore.GetAllByStatus | p99 | 231ms | 201ms | -30ms | -12.96
| ChannelStore.GetChannels | p99 | 227ms | 198ms | -29ms | -12.80
| ChannelStore.GetPublicChannelsForTeam | p99 | 243ms | 212ms | -31ms | -12.76
| PostStore.GetPostsAfter | p99 | 221ms | 193ms | -28ms | -12.66
| DraftStore.Get | p99 | 239ms | 209ms | -30ms | -12.56
| ChannelStore.GetForPost | p99 | 241ms | 211ms | -30ms | -12.47
| ThreadStore.GetTeamsUnreadForUser | p99 | 233ms | 204ms | -29ms | -12.44
| UserStore.AutocompleteUsersInChannel | p99 | 450ms | 394ms | -56ms | -12.44
| UserStore.Update | p99 | 249ms | 219ms | -30ms | -12.06
| PostStore.SearchPostsForUser | p99 | 3.758s | 3.318s | -440ms | -11.71
| UserStore.GetByUsername | p99 | 208ms | 184ms | -24ms | -11.54
| StatusStore.GetByIds | p99 | 243ms | 215ms | -28ms | -11.53
| GroupStore.GetByName | p99 | 107ms | 95ms | -12ms | -11.26
| UserStore.GetAllProfiles | p99 | 100ms | 89ms | -11ms | -10.95
| ChannelStore.GetMemberLastViewedAt | p99 | 106ms | 95ms | -11ms | -10.33
| PostStore.GetPostIdAfterTime | p99 | 130ms | 117ms | -13ms | -9.98
| ChannelStore.CreateInitialSidebarCategories | p99 | 425ms | 383ms | -42ms | -9.87
| PreferenceStore.Save | p99 | 270ms | 244ms | -26ms | -9.63
| UserStore.Search | p99 | 268ms | 244ms | -24ms | -8.95
| WebhookStore.GetOutgoingByTeam | p99 | 238ms | 217ms | -21ms | -8.83
| UserStore.UpdateUpdateAt | p99 | 85ms | 78ms | -7ms | -8.26
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 234ms | 215ms | -19ms | -8.14
| PostStore.Save | p99 | 412ms | 379ms | -33ms | -8.01
| UserStore.Count | p99 | 192ms | 177ms | -15ms | -7.82
| TeamStore.GetMember | p99 | 95ms | 88ms | -7ms | -7.40
| ThreadStore.UpdateMembership | p99 | 97ms | 90ms | -7ms | -7.19
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 85ms | 79ms | -6ms | -7.06
| SessionStore.Get | p99 | 232ms | 217ms | -15ms | -6.45
| SessionStore.Save | p99 | 206ms | 193ms | -13ms | -6.30
| ThreadStore.MarkAsRead | p99 | 97ms | 91ms | -6ms | -6.19
| PostStore.GetPosts | p99 | 98ms | 92ms | -6ms | -6.10
| PostStore.GetPostsSince | p99 | 247ms | 232ms | -15ms | -6.08
| ChannelStore.GetMemberCount | p99 | 242ms | 228ms | -14ms | -5.79
| ChannelStore.Save | p99 | 441ms | 416ms | -25ms | -5.66
| ThreadStore.Get | p99 | 230ms | 217ms | -13ms | -5.66
| ChannelStore.GetMemberForPost | p99 | 244ms | 231ms | -13ms | -5.32
| SessionStore.UpdateLastActivityAt | p99 | 96ms | 91ms | -5ms | -5.20
| ChannelStore.GetMember | p99 | 98ms | 93ms | -5ms | -5.11
| PostStore.SetPostReminder | p99 | 243ms | 231ms | -12ms | -4.93
| ProductNoticesStore.View | p99 | 947ms | 902ms | -45ms | -4.75
| UserStore.TryIncrementFailedPasswordAttempts | p99 | 86ms | 82ms | -4ms | -4.63
| SystemStore.GetByName | p99 | 91ms | 87ms | -4ms | -4.38
| PostStore.GetVisiblePostIdAroundTime | p99 | 93ms | 89ms | -4ms | -4.32
| PostStore.Delete | p99 | 473ms | 453ms | -20ms | -4.23
| SessionStore.GetSessionsExpired | p99 | 48ms | 46ms | -2ms | -4.16
| FileInfoStore.GetByIds | p99 | 221ms | 212ms | -9ms | -4.07
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 99ms | 95ms | -4ms | -4.03
| FileInfoStore.AttachToPost | p99 | 219ms | 211ms | -8ms | -3.66
| UserStore.UpdateLastLogin | p99 | 84ms | 81ms | -3ms | -3.58
| UserStore.UpdateFailedPasswordAttempts | p99 | 90ms | 87ms | -3ms | -3.32
| AuditStore.Save | p99 | 91ms | 88ms | -3ms | -3.29
| ChannelStore.UpdateLastViewedAt | p99 | 95ms | 92ms | -3ms | -3.16
| StatusStore.UpdateLastActivityAt | p99 | 96ms | 93ms | -3ms | -3.13
| ThreadStore.MarkAllAsReadByChannels | p99 | 98ms | 95ms | -3ms | -3.06
| ChannelStore.IncrementMentionCount | p99 | 98ms | 95ms | -3ms | -3.05
| ThreadStore.MaintainMembership | p99 | 239ms | 232ms | -7ms | -2.93
| StatusStore.UpdateExpiredDNDStatuses | p99 | 105ms | 102ms | -3ms | -2.85
| UserStore.GetAllProfilesInChannel | p99 | 2.271s | 2.21s | -61ms | -2.69
| PostStore.GetPostReminderMetadata | p99 | 92ms | 90ms | -2ms | -2.18
| LinkMetadataStore.Save | p99 | 93ms | 91ms | -2ms | -2.15
| ChannelStore.CreateDirectChannel | p99 | 883ms | 874ms | -9ms | -1.02
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | avg | 5ms | 30ms | 25ms | 487.76
| listCPAFields | avg | 22ms | 35ms | 13ms | 58.76
| getPropertyFields | avg | 28ms | 37ms | 9ms | 32.33
| deleteChannelBookmark | avg | 25ms | 32ms | 7ms | 27.57
| updateCategoriesForTeamForUser | avg | 153ms | 189ms | 36ms | 23.61
| createSchedulePost | avg | 21ms | 26ms | 5ms | 23.27
| getChannelMembers | avg | 12ms | 14ms | 2ms | 16.94
| root | avg | 14ms | 16ms | 2ms | 14.24
| getTeamStats | avg | 92ms | 96ms | 4ms | 4.34
| searchPostsInTeam | avg | 329ms | 338ms | 9ms | 2.74
| createDirectChannel | avg | 597ms | 604ms | 7ms | 1.17
| uploadFileStream | avg | 583ms | 589ms | 6ms | 1.03
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | p99 | 47ms | 239ms | 192ms | 406.60
| getFilteredUsersStats | p99 | 25ms | 98ms | 73ms | 293.69
| getChannelMembers | p99 | 25ms | 95ms | 70ms | 283.40
| deleteChannelBookmark | p99 | 95ms | 236ms | 141ms | 147.65
| updateReadStateAllThreadsByUser | p99 | 49ms | 96ms | 47ms | 95.76
| createSchedulePost | p99 | 241ms | 350ms | 109ms | 45.22
| root | p99 | 203ms | 221ms | 18ms | 8.86
| updateCategoriesForTeamForUser | p99 | 1.728s | 1.878s | 150ms | 8.68
| getTeamStats | p99 | 403ms | 435ms | 32ms | 7.95
| getPropertyFields | p99 | 238ms | 241ms | 3ms | 1.26
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listCPAValues | avg | 36ms | 0s | -36ms | -100.59
| getConfig | avg | 167ms | 0s | -167ms | -99.71
| channelMemberCountsByGroup | avg | 18ms | 0s | -18ms | -99.33
| getAgentsStatus | avg | 20ms | 0s | -20ms | -98.25
| autocompleteEmojis | avg | 3ms | 0s | -3ms | -94.69
| getAgents | avg | 7ms | 0s | -7ms | -94.05
| handleCheckCWSConnection | avg | 142ms | 38ms | -104ms | -73.04
| getServerLimits | avg | 29ms | 17ms | -12ms | -41.50
| createCategoryForTeamForUser | avg | 101ms | 63ms | -38ms | -37.58
| followThreadByUser | avg | 78ms | 49ms | -29ms | -37.25
| logout | avg | 208ms | 131ms | -77ms | -36.98
| createChannelBookmark | avg | 92ms | 64ms | -28ms | -30.52
| patchPost | avg | 176ms | 125ms | -51ms | -29.04
| updateChannelBookmark | avg | 50ms | 36ms | -14ms | -28.06
| setPostReminder | avg | 156ms | 118ms | -38ms | -24.35
| getAnalytics | avg | 113ms | 87ms | -26ms | -23.08
| deletePost | avg | 141ms | 109ms | -32ms | -22.64
| getChannel | avg | 36ms | 28ms | -8ms | -22.37
| getPostsForChannel | avg | 225ms | 178ms | -47ms | -20.85
| autocompleteChannelsForTeamForSearch | avg | 82ms | 65ms | -17ms | -20.63
| getChannelUnread | avg | 21ms | 17ms | -4ms | -18.96
| getPostThread | avg | 96ms | 78ms | -18ms | -18.79
| deleteDraft | avg | 22ms | 18ms | -4ms | -18.16
| searchGroupChannels | avg | 22ms | 18ms | -4ms | -18.11
| getUser | avg | 22ms | 18ms | -4ms | -17.91
| viewChannel | avg | 85ms | 70ms | -15ms | -17.69
| updateReadStateThreadByUser | avg | 184ms | 153ms | -31ms | -16.82
| getTeamsForUser | avg | 12ms | 10ms | -2ms | -16.13
| getChannelMembersForTeamForUser | avg | 19ms | 16ms | -3ms | -15.95
| getUsers | avg | 19ms | 16ms | -3ms | -15.45
| getChannelsForTeamForUser | avg | 19ms | 16ms | -3ms | -15.45
| unfollowThreadByUser | avg | 79ms | 67ms | -12ms | -15.28
| getChannelMembersForUser | avg | 13ms | 11ms | -2ms | -15.21
| getPreferences | avg | 13ms | 11ms | -2ms | -15.17
| addChannelMember | avg | 629ms | 535ms | -94ms | -14.94
| getAllTeams | avg | 14ms | 12ms | -2ms | -14.51
| getTeamScheduledPosts | avg | 21ms | 18ms | -3ms | -14.40
| getDrafts | avg | 21ms | 18ms | -3ms | -14.16
| getThreadsForUser | avg | 21ms | 18ms | -3ms | -13.99
| getCategoriesForTeamForUser | avg | 22ms | 19ms | -3ms | -13.88
| listChannelBookmarksForChannel | avg | 15ms | 13ms | -2ms | -13.50
| getClientConfig | avg | 24ms | 21ms | -3ms | -12.71
| getChannelMember | avg | 24ms | 21ms | -3ms | -12.60
| getTeamsUnreadForUser | avg | 24ms | 21ms | -3ms | -12.44
| createGroupChannel | avg | 1.028s | 908ms | -120ms | -11.67
| createChannel | avg | 693ms | 614ms | -79ms | -11.39
| getPostsForChannelAroundLastUnread | avg | 63ms | 56ms | -7ms | -11.13
| getUsersByNames | avg | 18ms | 16ms | -2ms | -11.00
| createPost | avg | 782ms | 698ms | -84ms | -10.74
| saveReaction | avg | 77ms | 69ms | -8ms | -10.33
| addTeamMember | avg | 1.509s | 1.36s | -149ms | -9.87
| upsertDraft | avg | 20ms | 18ms | -2ms | -9.81
| autocompleteUsers | avg | 82ms | 75ms | -7ms | -8.58
| getPublicChannelsForTeam | avg | 38ms | 35ms | -3ms | -7.97
| searchAllChannels | avg | 60ms | 56ms | -4ms | -6.65
| searchUsers | avg | 63ms | 59ms | -4ms | -6.37
| updatePreferences | avg | 47ms | 44ms | -3ms | -6.32
| login | avg | 166ms | 156ms | -10ms | -6.01
| createUser | avg | 409ms | 388ms | -21ms | -5.13
| getProfileImage | avg | 70ms | 67ms | -3ms | -4.27
| getFileThumbnail | avg | 72ms | 69ms | -3ms | -4.15
| getFilePreview | avg | 78ms | 75ms | -3ms | -3.86
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 10ms | 0s | -10ms | -101.01
| listCPAValues | p99 | 411ms | 0s | -411ms | -100.06
| channelMemberCountsByGroup | p99 | 211ms | 0s | -211ms | -100.01
| getConfig | p99 | 248ms | 0s | -248ms | -99.80
| getAgentsStatus | p99 | 242ms | 5ms | -237ms | -97.73
| getAgents | p99 | 94ms | 5ms | -89ms | -94.68
| logout | p99 | 3.2s | 481ms | -2.719s | -84.96
| handleCheckCWSConnection | p99 | 249ms | 50ms | -199ms | -80.08
| getAnalytics | p99 | 249ms | 100ms | -149ms | -59.96
| listCPAFields | p99 | 243ms | 99ms | -144ms | -59.35
| patchPost | p99 | 3.269s | 1.57s | -1.699s | -51.97
| updateChannelBookmark | p99 | 463ms | 223ms | -240ms | -51.89
| setPostReminder | p99 | 1.78s | 872ms | -908ms | -51.01
| createCategoryForTeamForUser | p99 | 486ms | 243ms | -243ms | -49.97
| updateChannelBookmarkSortOrder | p99 | 49ms | 25ms | -24ms | -49.20
| followThreadByUser | p99 | 700ms | 373ms | -327ms | -46.71
| addChannelMember | p99 | 4.085s | 2.482s | -1.603s | -39.25
| searchAllChannels | p99 | 407ms | 250ms | -157ms | -38.55
| getChannel | p99 | 400ms | 250ms | -150ms | -37.47
| updateReadStateThreadByUser | p99 | 2.032s | 1.414s | -618ms | -30.42
| getPostsForChannel | p99 | 3.317s | 2.321s | -996ms | -30.03
| unfollowThreadByUser | p99 | 800ms | 565ms | -235ms | -29.37
| autocompleteChannelsForTeamForSearch | p99 | 606ms | 434ms | -172ms | -28.37
| getUser | p99 | 346ms | 249ms | -97ms | -28.02
| saveReaction | p99 | 647ms | 471ms | -176ms | -27.22
| getUserStatusesByIds | p99 | 130ms | 95ms | -35ms | -26.93
| getPostsForChannelAroundLastUnread | p99 | 714ms | 534ms | -180ms | -25.20
| getTeamsForUser | p99 | 179ms | 134ms | -45ms | -25.13
| getChannelsForUser | p99 | 143ms | 109ms | -34ms | -23.75
| getPreferences | p99 | 190ms | 146ms | -44ms | -23.17
| login | p99 | 1.26s | 985ms | -275ms | -21.83
| getTeamsUnreadForUser | p99 | 306ms | 240ms | -66ms | -21.55
| getPostThread | p99 | 994ms | 792ms | -202ms | -20.33
| searchUsers | p99 | 308ms | 248ms | -60ms | -19.46
| createDirectChannel | p99 | 3.556s | 2.888s | -668ms | -18.79
| searchGroupChannels | p99 | 245ms | 199ms | -46ms | -18.76
| getChannelMembersForUser | p99 | 176ms | 144ms | -32ms | -18.13
| viewChannel | p99 | 915ms | 750ms | -165ms | -18.04
| getAllTeams | p99 | 203ms | 167ms | -36ms | -17.73
| getTeamMembersForUser | p99 | 176ms | 148ms | -28ms | -15.88
| getUsers | p99 | 286ms | 241ms | -45ms | -15.75
| getUsersByIds | p99 | 66ms | 56ms | -10ms | -15.06
| listChannelBookmarksForChannel | p99 | 207ms | 177ms | -30ms | -14.48
| deletePost | p99 | 947ms | 810ms | -137ms | -14.47
| getChannelMembersForTeamForUser | p99 | 229ms | 196ms | -33ms | -14.42
| getTeamMember | p99 | 176ms | 153ms | -23ms | -13.07
| autocompleteUsers | p99 | 465ms | 406ms | -59ms | -12.68
| getChannelStats | p99 | 179ms | 157ms | -22ms | -12.27
| getChannelMember | p99 | 268ms | 237ms | -31ms | -11.56
| getUsersByNames | p99 | 221ms | 196ms | -25ms | -11.31
| getThreadsForUser | p99 | 241ms | 214ms | -27ms | -11.21
| getChannelsForTeamForUser | p99 | 234ms | 208ms | -26ms | -11.10
| deleteDraft | p99 | 248ms | 222ms | -26ms | -10.47
| getDrafts | p99 | 248ms | 222ms | -26ms | -10.47
| getChannelUnread | p99 | 239ms | 215ms | -24ms | -10.02
| getPublicChannelsForTeam | p99 | 243ms | 220ms | -23ms | -9.45
| addTeamMember | p99 | 9.412s | 8.524s | -888ms | -9.43
| getFileThumbnail | p99 | 423ms | 385ms | -38ms | -8.98
| createGroupChannel | p99 | 4.978s | 4.537s | -441ms | -8.86
| createChannelBookmark | p99 | 485ms | 448ms | -37ms | -7.64
| createPost | p99 | 4.86s | 4.534s | -326ms | -6.71
| getCategoriesForTeamForUser | p99 | 240ms | 224ms | -16ms | -6.68
| updatePreferences | p99 | 422ms | 394ms | -28ms | -6.64
| upsertDraft | p99 | 226ms | 212ms | -14ms | -6.19
| getFilePreview | p99 | 453ms | 426ms | -27ms | -5.96
| getTeamScheduledPosts | p99 | 240ms | 226ms | -14ms | -5.83
| searchPostsInTeam | p99 | 4.245s | 4.04s | -205ms | -4.83
| createChannel | p99 | 4.513s | 4.35s | -163ms | -3.61
| createUser | p99 | 2.346s | 2.262s | -84ms | -3.58
| getClientConfig | p99 | 241ms | 235ms | -6ms | -2.49
| uploadFileStream | p99 | 2.335s | 2.308s | -27ms | -1.16
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 88ms | -3ms | -3.293
| BotStore.Get |  Avg| 14ms| 6ms | -8ms | -56.276
| |  P99| 410ms| 47ms | -363ms | -88.537
| ChannelBookmarkStore.Delete |  Avg| 13ms| 17ms | 4ms | 31.719
| |  P99| 48ms| 95ms | 47ms | 96.907
| ChannelBookmarkStore.Get |  Avg| 10ms| 15ms | 5ms | 49.682
| |  P99| 90ms| 189ms | 99ms | 110.304
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 13ms| 11ms | -2ms | -15.528
| |  P99| 175ms| 134ms | -41ms | -23.418
| ChannelBookmarkStore.Save |  Avg| 58ms| 35ms | -23ms | -39.409
| |  P99| 405ms| 230ms | -175ms | -43.212
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 48ms| 24ms | -24ms | -49.739
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 8ms| 7ms | -1ms | -12.788
| |  P99| 85ms| 79ms | -6ms | -7.061
| ChannelStore.AnalyticsCountAll |  Avg| 39ms| 29ms | -10ms | -25.910
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 59ms| 54ms | -5ms | -8.468
| |  P99| 388ms| 247ms | -141ms | -36.342
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 82ms| 65ms | -17ms | -20.811
| |  P99| 557ms| 430ms | -127ms | -22.802
| ChannelStore.CreateDirectChannel |  Avg| 102ms| 94ms | -8ms | -7.826
| |  P99| 883ms| 874ms | -9ms | -1.020
| ChannelStore.CreateInitialSidebarCategories |  Avg| 40ms| 35ms | -5ms | -12.475
| |  P99| 425ms| 383ms | -42ms | -9.872
| ChannelStore.CreateSidebarCategory |  Avg| 86ms| 49ms | -37ms | -43.238
| |  P99| 486ms| 243ms | -243ms | -49.974
| ChannelStore.Get |  Avg| 30ms| 24ms | -6ms | -20.217
| |  P99| 355ms| 238ms | -117ms | -32.995
| ChannelStore.GetAllChannelMembersForUser |  Avg| 16ms| 14ms | -2ms | -12.275
| |  P99| 186ms| 143ms | -43ms | -23.176
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 32ms| 27ms | -5ms | -15.865
| |  P99| 409ms| 329ms | -80ms | -19.543
| ChannelStore.GetBoardChannel |  Avg| 16ms| 14ms | -2ms | -12.618
| |  P99| 207ms| 173ms | -34ms | -16.395
| ChannelStore.GetByName |  Avg| 15ms| 13ms | -2ms | -13.682
| |  P99| 173ms| 126ms | -47ms | -27.097
| ChannelStore.GetChannelUnread |  Avg| 19ms| 16ms | -3ms | -15.567
| |  P99| 227ms| 194ms | -33ms | -14.550
| ChannelStore.GetChannels |  Avg| 19ms| 16ms | -3ms | -16.041
| |  P99| 227ms| 198ms | -29ms | -12.803
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 10ms | -1ms | -9.063
| |  P99| 124ms| 99ms | -25ms | -20.123
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 14ms| 12ms | -2ms | -14.421
| |  P99| 195ms| 145ms | -50ms | -25.653
| ChannelStore.GetFileCount |  Avg| 16ms| 14ms | -2ms | -12.722
| |  P99| 192ms| 146ms | -46ms | -23.905
| ChannelStore.GetForPost |  Avg| 23ms| 19ms | -4ms | -17.439
| |  P99| 241ms| 211ms | -30ms | -12.467
| ChannelStore.GetGuestCount |  Avg| 15ms| 13ms | -2ms | -13.456
| |  P99| 198ms| 154ms | -44ms | -22.176
| ChannelStore.GetMany |  Avg| 29ms| 41ms | 12ms | 42.068
| |  P99| 335ms| 400ms | 65ms | 19.402
| ChannelStore.GetMember |  Avg| 10ms| 9ms | -1ms | -9.944
| |  P99| 98ms| 93ms | -5ms | -5.112
| ChannelStore.GetMemberCount |  Avg| 40ms| 37ms | -3ms | -7.495
| |  P99| 242ms| 228ms | -14ms | -5.792
| ChannelStore.GetMemberCountsByGroup |  Avg| 18ms| 0s | -18ms | -98.647
| |  P99| 206ms| 0s | -206ms | -99.764
| ChannelStore.GetMemberForPost |  Avg| 44ms| 41ms | -3ms | -6.862
| |  P99| 244ms| 231ms | -13ms | -5.324
| ChannelStore.GetMemberLastViewedAt |  Avg| 9ms| 8ms | -1ms | -10.625
| |  P99| 106ms| 95ms | -11ms | -10.331
| ChannelStore.GetMembers |  Avg| 11ms| 13ms | 2ms | 17.654
| |  P99| 25ms| 95ms | 70ms | 283.402
| ChannelStore.GetMembersForUser |  Avg| 18ms| 15ms | -3ms | -16.498
| |  P99| 222ms| 187ms | -35ms | -15.790
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 3ms| 23ms | 20ms | 623.463
| |  P99| 5ms| 98ms | 93ms | 1878.788
| ChannelStore.GetMembersForUserWithPagination |  Avg| 13ms| 11ms | -2ms | -15.716
| |  P99| 166ms| 130ms | -36ms | -21.730
| ChannelStore.GetPinnedPostCount |  Avg| 17ms| 13ms | -4ms | -24.085
| |  P99| 226ms| 174ms | -52ms | -23.051
| ChannelStore.GetPublicChannelsForTeam |  Avg| 36ms| 33ms | -3ms | -8.337
| |  P99| 243ms| 212ms | -31ms | -12.762
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 20ms| 18ms | -2ms | -9.794
| |  P99| 234ms| 215ms | -19ms | -8.136
| ChannelStore.GetSidebarCategory |  Avg| 30ms| 27ms | -3ms | -9.958
| |  P99| 490ms| 239ms | -251ms | -51.212
| ChannelStore.GetTeamChannels |  Avg| 53ms| 50ms | -3ms | -5.684
| |  P99| 403ms| 230ms | -173ms | -42.978
| ChannelStore.IncrementMentionCount |  Avg| 10ms| 9ms | -1ms | -9.584
| |  P99| 98ms| 95ms | -3ms | -3.049
| ChannelStore.Save |  Avg| 54ms| 49ms | -5ms | -9.325
| |  P99| 441ms| 416ms | -25ms | -5.664
| ChannelStore.SaveMember |  Avg| 83ms| 71ms | -12ms | -14.512
| |  P99| 831ms| 627ms | -204ms | -24.546
| ChannelStore.SearchGroupChannels |  Avg| 21ms| 18ms | -3ms | -13.958
| |  P99| 237ms| 190ms | -47ms | -19.866
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 10ms | -1ms | -8.900
| |  P99| 95ms| 92ms | -3ms | -3.157
| ChannelStore.UpdateSidebarCategories |  Avg| 83ms| 119ms | 36ms | 43.633
| |  P99| 743ms| 862ms | 119ms | 16.027
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 10ms| 9ms | -1ms | -9.846
| |  P99| 99ms| 95ms | -4ms | -4.034
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 17ms| 14ms | -3ms | -17.603
| |  P99| 168ms| 131ms | -37ms | -22.061
| CommandWebhookStore.Cleanup |  Avg| 8ms| 31ms | 23ms | 290.498
| |  P99| 48ms| 97ms | 49ms | 101.032
| DraftStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 100ms| 99ms | -1ms | -1.001
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 20ms| 27ms | 7ms | 34.217
| |  P99| 202ms| 222ms | 20ms | 9.901
| DraftStore.Get |  Avg| 21ms| 17ms | -4ms | -19.447
| |  P99| 239ms| 209ms | -30ms | -12.556
| DraftStore.GetDraftsForUser |  Avg| 20ms| 17ms | -3ms | -15.113
| |  P99| 238ms| 206ms | -32ms | -13.463
| DraftStore.Upsert |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 136ms| 114ms | -22ms | -16.186
| EmojiStore.GetByName |  Avg| 15ms| 12ms | -3ms | -19.928
| |  P99| 208ms| 158ms | -50ms | -24.066
| EmojiStore.GetMultipleByName |  Avg| 24ms| 4ms | -20ms | -82.073
| |  P99| 95ms| 23ms | -72ms | -75.591
| EmojiStore.Search |  Avg| 3ms| 0s | -3ms | -96.376
| |  P99| 10ms| 0s | -10ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 22ms| 20ms | -2ms | -9.244
| |  P99| 219ms| 211ms | -8ms | -3.655
| FileInfoStore.Get |  Avg| 16ms| 14ms | -2ms | -12.683
| |  P99| 207ms| 180ms | -27ms | -13.049
| FileInfoStore.GetByIds |  Avg| 16ms| 15ms | -1ms | -6.209
| |  P99| 221ms| 212ms | -9ms | -4.065
| FileInfoStore.GetForPost |  Avg| 11ms| 7ms | -4ms | -37.945
| |  P99| 100ms| 85ms | -15ms | -15.062
| FileInfoStore.Save |  Avg| 16ms| 15ms | -1ms | -6.170
| |  P99| 165ms| 127ms | -38ms | -23.008
| FileInfoStore.SetContent |  Avg| 24ms| 23ms | -1ms | -4.138
| |  P99| 222ms| 234ms | 12ms | 5.399
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 9ms| 8ms | -1ms | -10.611
| |  P99| 128ms| 94ms | -34ms | -26.493
| GroupStore.GetByName |  Avg| 10ms| 9ms | -1ms | -10.280
| |  P99| 107ms| 95ms | -12ms | -11.258
| GroupStore.GetGroups |  Avg| 16ms| 13ms | -3ms | -18.961
| |  P99| 215ms| 169ms | -46ms | -21.366
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 19ms| 3ms | -16ms | -82.803
| |  P99| 25ms| 5ms | -20ms | -80.462
| JobStore.GetAllByStatus |  Avg| 19ms| 17ms | -2ms | -10.479
| |  P99| 231ms| 201ms | -30ms | -12.962
| JobStore.GetAllByTypePage |  Avg| 15ms| 29ms | 14ms | 95.303
| |  P99| 49ms| 239ms | 190ms | 387.199
| JobStore.GetCountByStatusAndType |  Avg| 14ms| 12ms | -2ms | -13.977
| |  P99| 147ms| 98ms | -49ms | -33.277
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 10ms | 2ms | 24.995
| |  P99| 80ms| 153ms | 73ms | 90.966
| JobStore.Save |  Avg| 10ms| 11ms | 1ms | 10.263
| |  P99| 80ms| 96ms | 16ms | 20.000
| JobStore.UpdateOptimistically |  Avg| 11ms| 12ms | 1ms | 9.520
| |  P99| 68ms| 99ms | 31ms | 45.263
| JobStore.UpdateStatus |  Avg| 12ms| 16ms | 4ms | 32.873
| |  P99| 97ms| 186ms | 89ms | 91.286
| JobStore.UpdateStatusOptimistically |  Avg| 12ms| 15ms | 3ms | 25.931
| |  P99| 160ms| 98ms | -62ms | -38.745
| LicenseStore.GetAll |  Avg| 17ms| 2ms | -15ms | -88.000
| |  P99| 49ms| 5ms | -44ms | -89.341
| LinkMetadataStore.Get |  Avg| 15ms| 12ms | -3ms | -19.632
| |  P99| 221ms| 167ms | -54ms | -24.434
| LinkMetadataStore.Save |  Avg| 16ms| 11ms | -5ms | -31.941
| |  P99| 93ms| 91ms | -2ms | -2.153
| PostAcknowledgementStore.GetForPost |  Avg| 14ms| 10ms | -4ms | -28.664
| |  P99| 218ms| 157ms | -61ms | -28.045
| PostAcknowledgementStore.GetForPosts |  Avg| 24ms| 19ms | -5ms | -21.137
| |  P99| 374ms| 247ms | -127ms | -33.980
| PostPersistentNotificationStore.DeleteExpired |  Avg| 10ms| 14ms | 4ms | 40.925
| |  P99| 90ms| 154ms | 64ms | 71.372
| PostPersistentNotificationStore.Get |  Avg| 11ms| 19ms | 8ms | 74.048
| |  P99| 90ms| 154ms | 64ms | 71.372
| PostPersistentNotificationStore.GetSingle |  Avg| 13ms| 10ms | -3ms | -22.794
| |  P99| 211ms| 141ms | -70ms | -33.210
| PostPriorityStore.GetForPostWithContext |  Avg| 14ms| 11ms | -3ms | -21.341
| |  P99| 216ms| 155ms | -61ms | -28.186
| PostPriorityStore.GetForPosts |  Avg| 25ms| 20ms | -5ms | -20.241
| |  P99| 380ms| 248ms | -132ms | -34.734
| PostStore.AnalyticsPostCount |  Avg| 491ms| 373ms | -118ms | -24.017
| |  P99| 2.455s| 980ms | -1.475s | -60.082
| PostStore.AnalyticsPostCountByTeam |  Avg| 9ms| 1ms | -8ms | -84.790
| |  P99| 10ms| 5ms | -5ms | -50.241
| PostStore.Delete |  Avg| 86ms| 58ms | -28ms | -32.693
| |  P99| 473ms| 453ms | -20ms | -4.225
| PostStore.Get |  Avg| 37ms| 31ms | -6ms | -16.320
| |  P99| 390ms| 256ms | -134ms | -34.329
| PostStore.GetEtag |  Avg| 17ms| 14ms | -3ms | -17.752
| |  P99| 215ms| 182ms | -33ms | -15.335
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 12ms| 11ms | -1ms | -8.176
| |  P99| 130ms| 117ms | -13ms | -9.978
| PostStore.GetPostReminderMetadata |  Avg| 17ms| 14ms | -3ms | -17.863
| |  P99| 92ms| 90ms | -2ms | -2.176
| PostStore.GetPostReminders |  Avg| 6ms| 5ms | -1ms | -15.496
| |  P99| 82ms| 45ms | -37ms | -45.399
| PostStore.GetPosts |  Avg| 10ms| 9ms | -1ms | -9.912
| |  P99| 98ms| 92ms | -6ms | -6.096
| PostStore.GetPostsAfter |  Avg| 17ms| 16ms | -1ms | -5.740
| |  P99| 221ms| 193ms | -28ms | -12.661
| PostStore.GetPostsBefore |  Avg| 19ms| 16ms | -3ms | -15.922
| |  P99| 220ms| 191ms | -29ms | -13.176
| PostStore.GetPostsByThread |  Avg| 21ms| 17ms | -4ms | -19.227
| |  P99| 228ms| 171ms | -57ms | -25.050
| PostStore.GetPostsSince |  Avg| 34ms| 31ms | -3ms | -8.748
| |  P99| 247ms| 232ms | -15ms | -6.081
| PostStore.GetSingle |  Avg| 15ms| 11ms | -4ms | -26.737
| |  P99| 219ms| 163ms | -56ms | -25.532
| PostStore.GetVisiblePostIdAroundTime |  Avg| 9ms| 8ms | -1ms | -11.268
| |  P99| 93ms| 89ms | -4ms | -4.321
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 41ms| 38ms | -3ms | -7.239
| |  P99| 412ms| 379ms | -33ms | -8.010
| PostStore.SearchPostsForUser |  Avg| 288ms| 302ms | 14ms | 4.857
| |  P99| 3.758s| 3.318s | -440ms | -11.708
| PostStore.SetPostReminder |  Avg| 48ms| 35ms | -13ms | -27.106
| |  P99| 243ms| 231ms | -12ms | -4.929
| PostStore.Update |  Avg| 30ms| 31ms | 1ms | 3.334
| |  P99| 238ms| 239ms | 1ms | 0.421
| PreferenceStore.DeleteCategoryAndName |  Avg| 14ms| 24ms | 10ms | 71.968
| |  P99| 49ms| 222ms | 173ms | 355.479
| PreferenceStore.Get |  Avg| 15ms| 12ms | -3ms | -20.193
| |  P99| 204ms| 163ms | -41ms | -20.079
| PreferenceStore.GetAll |  Avg| 13ms| 10ms | -3ms | -23.878
| |  P99| 177ms| 120ms | -57ms | -32.221
| PreferenceStore.Save |  Avg| 32ms| 29ms | -3ms | -9.462
| |  P99| 270ms| 244ms | -26ms | -9.630
| ProductNoticesStore.ClearOldNotices |  Avg| 46ms| 87ms | 41ms | 89.091
| |  P99| 50ms| 248ms | 198ms | 397.990
| ProductNoticesStore.GetViews |  Avg| 15ms| 6ms | -9ms | -60.042
| |  P99| 25ms| 10ms | -15ms | -60.347
| ProductNoticesStore.View |  Avg| 115ms| 102ms | -13ms | -11.327
| |  P99| 947ms| 902ms | -45ms | -4.753
| PropertyFieldStore.SearchPropertyFields |  Avg| 10ms| 13ms | 3ms | 30.587
| |  P99| 111ms| 216ms | 105ms | 94.753
| PropertyGroupStore.Get |  Avg| 11ms| 15ms | 4ms | 34.896
| |  P99| 160ms| 96ms | -64ms | -40.080
| PropertyValueStore.SearchPropertyValues |  Avg| 16ms| 0s | -16ms | -101.402
| |  P99| 216ms| 0s | -216ms | -99.917
| ReactionStore.GetForPost |  Avg| 14ms| 12ms | -2ms | -14.339
| |  P99| 207ms| 151ms | -56ms | -27.050
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -110.252
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 37ms| 13ms | -24ms | -64.730
| |  P99| 248ms| 147ms | -101ms | -40.750
| RoleStore.GetByNames |  Avg| 47ms| 26ms | -21ms | -44.690
| |  P99| 246ms| 176ms | -70ms | -28.481
| ScheduledPostStore.CreateScheduledPost |  Avg| 14ms| 15ms | 1ms | 7.181
| |  P99| 85ms| 93ms | 8ms | 9.384
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 19ms| 14ms | -5ms | -26.020
| |  P99| 232ms| 93ms | -139ms | -60.043
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 10ms| 9ms | -1ms | -9.910
| |  P99| 121ms| 98ms | -23ms | -19.037
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 7ms| 4ms | -3ms | -40.782
| |  P99| 195ms| 40ms | -155ms | -79.692
| SessionStore.Get |  Avg| 21ms| 19ms | -2ms | -9.512
| |  P99| 232ms| 217ms | -15ms | -6.453
| SessionStore.GetLRUSessions |  Avg| 9ms| 8ms | -1ms | -10.850
| |  P99| 118ms| 94ms | -24ms | -20.300
| SessionStore.GetSessionsExpired |  Avg| 9ms| 8ms | -1ms | -11.036
| |  P99| 48ms| 46ms | -2ms | -4.156
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 15ms| 12ms | -3ms | -20.271
| |  P99| 211ms| 167ms | -44ms | -20.818
| SessionStore.Remove |  Avg| 15ms| 12ms | -3ms | -20.526
| |  P99| 142ms| 94ms | -48ms | -33.810
| SessionStore.Save |  Avg| 17ms| 16ms | -1ms | -5.718
| |  P99| 206ms| 193ms | -13ms | -6.299
| SessionStore.UpdateLastActivityAt |  Avg| 11ms| 10ms | -1ms | -9.069
| |  P99| 96ms| 91ms | -5ms | -5.204
| StatusStore.Get |  Avg| 14ms| 12ms | -2ms | -14.270
| |  P99| 200ms| 156ms | -44ms | -21.993
| StatusStore.GetByIds |  Avg| 23ms| 18ms | -5ms | -22.027
| |  P99| 243ms| 215ms | -28ms | -11.531
| StatusStore.SaveOrUpdate |  Avg| 13ms| 12ms | -1ms | -7.591
| |  P99| 118ms| 99ms | -19ms | -16.079
| StatusStore.SaveOrUpdateMany |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 213ms| 221ms | 8ms | 3.758
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 10ms| 12ms | 2ms | 19.279
| |  P99| 105ms| 102ms | -3ms | -2.850
| StatusStore.UpdateLastActivityAt |  Avg| 11ms| 10ms | -1ms | -9.360
| |  P99| 96ms| 93ms | -3ms | -3.134
| SystemStore.GetByName |  Avg| 8ms| 7ms | -1ms | -12.770
| |  P99| 91ms| 87ms | -4ms | -4.378
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 15ms| 11ms | -4ms | -27.549
| |  P99| 218ms| 160ms | -58ms | -26.598
| TeamStore.GetActiveMemberCount |  Avg| 73ms| 84ms | 11ms | 15.143
| |  P99| 242ms| 435ms | 193ms | 79.870
| TeamStore.GetAllPage |  Avg| 12ms| 10ms | -2ms | -16.981
| |  P99| 169ms| 103ms | -66ms | -39.072
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 12ms| 11ms | -1ms | -8.076
| |  P99| 177ms| 123ms | -54ms | -30.509
| TeamStore.GetMember |  Avg| 8ms| 7ms | -1ms | -11.913
| |  P99| 95ms| 88ms | -7ms | -7.401
| TeamStore.GetTeamsByUserId |  Avg| 12ms| 10ms | -2ms | -16.663
| |  P99| 169ms| 117ms | -52ms | -30.805
| TeamStore.GetTeamsForUser |  Avg| 11ms| 10ms | -1ms | -9.043
| |  P99| 147ms| 100ms | -47ms | -31.953
| TeamStore.GetTotalMemberCount |  Avg| 78ms| 76ms | -2ms | -2.548
| |  P99| 403ms| 435ms | 32ms | 7.950
| TeamStore.SaveMember |  Avg| 45ms| 41ms | -4ms | -8.913
| |  P99| 283ms| 246ms | -37ms | -13.088
| TemporaryPostStore.GetExpiredPosts |  Avg| 24ms| 18ms | -6ms | -25.322
| |  P99| 227ms| 96ms | -131ms | -57.585
| ThreadStore.Get |  Avg| 17ms| 13ms | -4ms | -22.863
| |  P99| 230ms| 217ms | -13ms | -5.664
| ThreadStore.GetMembershipForUser |  Avg| 16ms| 13ms | -3ms | -18.767
| |  P99| 219ms| 180ms | -39ms | -17.816
| ThreadStore.GetTeamsUnreadForUser |  Avg| 18ms| 15ms | -3ms | -16.963
| |  P99| 233ms| 204ms | -29ms | -12.443
| ThreadStore.GetThreadFollowers |  Avg| 15ms| 12ms | -3ms | -20.654
| |  P99| 213ms| 170ms | -43ms | -20.153
| ThreadStore.GetThreadForUser |  Avg| 27ms| 22ms | -5ms | -18.264
| |  P99| 338ms| 238ms | -100ms | -29.600
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 24ms| 21ms | -3ms | -12.383
| |  P99| 230ms| 194ms | -36ms | -15.670
| ThreadStore.GetThreadsForUser |  Avg| 21ms| 17ms | -4ms | -19.426
| |  P99| 230ms| 200ms | -30ms | -13.026
| ThreadStore.GetTotalThreads |  Avg| 12ms| 10ms | -2ms | -16.579
| |  P99| 163ms| 105ms | -58ms | -35.528
| ThreadStore.GetTotalUnreadMentions |  Avg| 13ms| 11ms | -2ms | -15.103
| |  P99| 187ms| 140ms | -47ms | -25.086
| ThreadStore.GetTotalUnreadThreads |  Avg| 12ms| 10ms | -2ms | -16.726
| |  P99| 159ms| 107ms | -52ms | -32.742
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 12ms| 10ms | -2ms | -16.535
| |  P99| 159ms| 101ms | -58ms | -36.545
| ThreadStore.MaintainMembership |  Avg| 24ms| 21ms | -3ms | -12.552
| |  P99| 239ms| 232ms | -7ms | -2.930
| ThreadStore.MarkAllAsReadByChannels |  Avg| 12ms| 11ms | -1ms | -8.476
| |  P99| 98ms| 95ms | -3ms | -3.058
| ThreadStore.MarkAllAsReadByTeam |  Avg| 15ms| 16ms | 1ms | 6.570
| |  P99| 49ms| 96ms | 47ms | 96.659
| ThreadStore.MarkAsRead |  Avg| 11ms| 10ms | -1ms | -9.085
| |  P99| 97ms| 91ms | -6ms | -6.185
| ThreadStore.UpdateMembership |  Avg| 11ms| 10ms | -1ms | -9.297
| |  P99| 97ms| 90ms | -7ms | -7.192
| TokenStore.Cleanup |  Avg| 9ms| 25ms | 16ms | 187.109
| |  P99| 48ms| 50ms | 2ms | 4.124
| UserAccessTokenStore.GetByToken |  Avg| 17ms| 10ms | -7ms | -40.810
| |  P99| 191ms| 83ms | -108ms | -56.616
| UserStore.AnalyticsActiveCount |  Avg| 34ms| 26ms | -8ms | -23.489
| |  P99| 50ms| 49ms | -1ms | -2.010
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 10ms | 8ms | 503.282
| |  P99| 5ms| 49ms | 44ms | 888.509
| UserStore.AutocompleteUsersInChannel |  Avg| 86ms| 80ms | -6ms | -6.982
| |  P99| 450ms| 394ms | -56ms | -12.441
| UserStore.Count |  Avg| 26ms| 24ms | -2ms | -7.759
| |  P99| 192ms| 177ms | -15ms | -7.821
| UserStore.Get |  Avg| 14ms| 12ms | -2ms | -14.725
| |  P99| 189ms| 151ms | -38ms | -20.083
| UserStore.GetAllProfiles |  Avg| 9ms| 8ms | -1ms | -10.628
| |  P99| 100ms| 89ms | -11ms | -10.954
| UserStore.GetAllProfilesInChannel |  Avg| 422ms| 403ms | -19ms | -4.506
| |  P99| 2.271s| 2.21s | -61ms | -2.686
| UserStore.GetByUsername |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 208ms| 184ms | -24ms | -11.538
| UserStore.GetForLogin |  Avg| 10ms| 9ms | -1ms | -9.570
| |  P99| 122ms| 99ms | -23ms | -18.839
| UserStore.GetMany |  Avg| 16ms| 11ms | -5ms | -30.319
| |  P99| 165ms| 87ms | -78ms | -47.411
| UserStore.GetProfileByIds |  Avg| 17ms| 14ms | -3ms | -17.906
| |  P99| 214ms| 180ms | -34ms | -15.894
| UserStore.GetProfilesByUsernames |  Avg| 17ms| 15ms | -2ms | -11.601
| |  P99| 211ms| 182ms | -29ms | -13.743
| UserStore.GetProfilesInChannel |  Avg| 22ms| 10ms | -12ms | -53.943
| |  P99| 227ms| 48ms | -179ms | -79.027
| UserStore.GetProfilesNotInChannel |  Avg| 17ms| 22ms | 5ms | 30.148
| |  P99| 95ms| 211ms | 116ms | 121.945
| UserStore.GetUnreadCount |  Avg| 15ms| 12ms | -3ms | -20.319
| |  P99| 212ms| 162ms | -50ms | -23.570
| UserStore.IsEmpty |  Avg| 5ms| 4ms | -1ms | -19.682
| |  P99| 69ms| 56ms | -13ms | -18.920
| UserStore.Save |  Avg| 168ms| 162ms | -6ms | -3.572
| |  P99| 653ms| 517ms | -136ms | -20.822
| UserStore.Search |  Avg| 60ms| 57ms | -3ms | -4.973
| |  P99| 268ms| 244ms | -24ms | -8.946
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 9ms| 8ms | -1ms | -11.447
| |  P99| 86ms| 82ms | -4ms | -4.632
| UserStore.Update |  Avg| 33ms| 25ms | -8ms | -24.404
| |  P99| 249ms| 219ms | -30ms | -12.056
| UserStore.UpdateFailedPasswordAttempts |  Avg| 10ms| 9ms | -1ms | -9.982
| |  P99| 90ms| 87ms | -3ms | -3.320
| UserStore.UpdateLastLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 84ms| 81ms | -3ms | -3.579
| UserStore.UpdateUpdateAt |  Avg| 9ms| 8ms | -1ms | -10.953
| |  P99| 85ms| 78ms | -7ms | -8.262
| UserTermsOfServiceStore.GetByUser |  Avg| 11ms| 9ms | -2ms | -18.925
| |  P99| 155ms| 101ms | -54ms | -34.919
| WebhookStore.GetOutgoingByTeam |  Avg| 21ms| 18ms | -3ms | -14.121
| |  P99| 238ms| 217ms | -21ms | -8.826
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 629ms| 535ms | -94ms | -14.942
| | P99| 4.085s| 2.482s | -1.603s | -39.246
| addTeamMember | Avg| 1.509s| 1.36s | -149ms | -9.875
| | P99| 9.412s| 8.524s | -888ms | -9.435
| autocompleteChannelsForTeamForSearch | Avg| 82ms| 65ms | -17ms | -20.633
| | P99| 606ms| 434ms | -172ms | -28.375
| autocompleteEmojis | Avg| 3ms| 0s | -3ms | -94.693
| | P99| 10ms| 0s | -10ms | -101.010
| autocompleteUsers | Avg| 82ms| 75ms | -7ms | -8.579
| | P99| 465ms| 406ms | -59ms | -12.678
| channelMemberCountsByGroup | Avg| 18ms| 0s | -18ms | -99.330
| | P99| 211ms| 0s | -211ms | -100.006
| createCategoryForTeamForUser | Avg| 101ms| 63ms | -38ms | -37.584
| | P99| 486ms| 243ms | -243ms | -49.974
| createChannel | Avg| 693ms| 614ms | -79ms | -11.392
| | P99| 4.513s| 4.35s | -163ms | -3.612
| createChannelBookmark | Avg| 92ms| 64ms | -28ms | -30.515
| | P99| 485ms| 448ms | -37ms | -7.637
| createDirectChannel | Avg| 597ms| 604ms | 7ms | 1.172
| | P99| 3.556s| 2.888s | -668ms | -18.786
| createEmoji | Avg| 5ms| 4ms | -1ms | -22.001
| | P99| 5ms| 5ms | 0s | 0.000
| createGroupChannel | Avg| 1.028s| 908ms | -120ms | -11.674
| | P99| 4.978s| 4.537s | -441ms | -8.860
| createPost | Avg| 782ms| 698ms | -84ms | -10.744
| | P99| 4.86s| 4.534s | -326ms | -6.707
| createSchedulePost | Avg| 21ms| 26ms | 5ms | 23.268
| | P99| 241ms| 350ms | 109ms | 45.217
| createUser | Avg| 409ms| 388ms | -21ms | -5.129
| | P99| 2.346s| 2.262s | -84ms | -3.581
| deleteChannelBookmark | Avg| 25ms| 32ms | 7ms | 27.573
| | P99| 95ms| 236ms | 141ms | 147.646
| deleteDraft | Avg| 22ms| 18ms | -4ms | -18.160
| | P99| 248ms| 222ms | -26ms | -10.468
| deletePost | Avg| 141ms| 109ms | -32ms | -22.639
| | P99| 947ms| 810ms | -137ms | -14.472
| followThreadByUser | Avg| 78ms| 49ms | -29ms | -37.251
| | P99| 700ms| 373ms | -327ms | -46.711
| getAgents | Avg| 7ms| 0s | -7ms | -94.049
| | P99| 94ms| 5ms | -89ms | -94.679
| getAgentsStatus | Avg| 20ms| 0s | -20ms | -98.253
| | P99| 242ms| 5ms | -237ms | -97.732
| getAllTeams | Avg| 14ms| 12ms | -2ms | -14.514
| | P99| 203ms| 167ms | -36ms | -17.727
| getAnalytics | Avg| 113ms| 87ms | -26ms | -23.079
| | P99| 249ms| 100ms | -149ms | -59.960
| getCategoriesForTeamForUser | Avg| 22ms| 19ms | -3ms | -13.883
| | P99| 240ms| 224ms | -16ms | -6.676
| getChannel | Avg| 36ms| 28ms | -8ms | -22.374
| | P99| 400ms| 250ms | -150ms | -37.468
| getChannelMember | Avg| 24ms| 21ms | -3ms | -12.604
| | P99| 268ms| 237ms | -31ms | -11.559
| getChannelMembers | Avg| 12ms| 14ms | 2ms | 16.937
| | P99| 25ms| 95ms | 70ms | 283.402
| getChannelMembersForTeamForUser | Avg| 19ms| 16ms | -3ms | -15.945
| | P99| 229ms| 196ms | -33ms | -14.424
| getChannelMembersForUser | Avg| 13ms| 11ms | -2ms | -15.213
| | P99| 176ms| 144ms | -32ms | -18.133
| getChannelStats | Avg| 8ms| 7ms | -1ms | -12.039
| | P99| 179ms| 157ms | -22ms | -12.272
| getChannelUnread | Avg| 21ms| 17ms | -4ms | -18.959
| | P99| 239ms| 215ms | -24ms | -10.021
| getChannelsForTeamForUser | Avg| 19ms| 16ms | -3ms | -15.445
| | P99| 234ms| 208ms | -26ms | -11.096
| getChannelsForUser | Avg| 11ms| 10ms | -1ms | -8.710
| | P99| 143ms| 109ms | -34ms | -23.746
| getClientConfig | Avg| 24ms| 21ms | -3ms | -12.712
| | P99| 241ms| 235ms | -6ms | -2.485
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 167ms| 0s | -167ms | -99.711
| | P99| 248ms| 0s | -248ms | -99.799
| getDrafts | Avg| 21ms| 18ms | -3ms | -14.155
| | P99| 248ms| 222ms | -26ms | -10.466
| getFilePreview | Avg| 78ms| 75ms | -3ms | -3.864
| | P99| 453ms| 426ms | -27ms | -5.964
| getFileThumbnail | Avg| 72ms| 69ms | -3ms | -4.147
| | P99| 423ms| 385ms | -38ms | -8.981
| getFilteredUsersStats | Avg| 21ms| 22ms | 1ms | 4.669
| | P99| 25ms| 98ms | 73ms | 293.687
| getJobsByType | Avg| 5ms| 30ms | 25ms | 487.757
| | P99| 47ms| 239ms | 192ms | 406.597
| getPostThread | Avg| 96ms| 78ms | -18ms | -18.785
| | P99| 994ms| 792ms | -202ms | -20.328
| getPostsForChannel | Avg| 225ms| 178ms | -47ms | -20.852
| | P99| 3.317s| 2.321s | -996ms | -30.031
| getPostsForChannelAroundLastUnread | Avg| 63ms| 56ms | -7ms | -11.128
| | P99| 714ms| 534ms | -180ms | -25.196
| getPreferences | Avg| 13ms| 11ms | -2ms | -15.165
| | P99| 190ms| 146ms | -44ms | -23.168
| getPrevTrialLicense | Avg| 3ms| 2ms | -1ms | -31.819
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 70ms| 67ms | -3ms | -4.268
| | P99| 466ms| 462ms | -4ms | -0.859
| getPropertyFields | Avg| 28ms| 37ms | 9ms | 32.325
| | P99| 238ms| 241ms | 3ms | 1.261
| getPublicChannelsForTeam | Avg| 38ms| 35ms | -3ms | -7.968
| | P99| 243ms| 220ms | -23ms | -9.448
| getServerLimits | Avg| 29ms| 17ms | -12ms | -41.501
| | P99| 50ms| 49ms | -1ms | -2.015
| getTeamMember | Avg| 14ms| 13ms | -1ms | -7.114
| | P99| 176ms| 153ms | -23ms | -13.070
| getTeamMembersForUser | Avg| 12ms| 11ms | -1ms | -8.090
| | P99| 176ms| 148ms | -28ms | -15.877
| getTeamScheduledPosts | Avg| 21ms| 18ms | -3ms | -14.404
| | P99| 240ms| 226ms | -14ms | -5.827
| getTeamStats | Avg| 92ms| 96ms | 4ms | 4.343
| | P99| 403ms| 435ms | 32ms | 7.950
| getTeamsForUser | Avg| 12ms| 10ms | -2ms | -16.131
| | P99| 179ms| 134ms | -45ms | -25.128
| getTeamsUnreadForUser | Avg| 24ms| 21ms | -3ms | -12.436
| | P99| 306ms| 240ms | -66ms | -21.552
| getThreadsForUser | Avg| 21ms| 18ms | -3ms | -13.993
| | P99| 241ms| 214ms | -27ms | -11.209
| getUser | Avg| 22ms| 18ms | -4ms | -17.908
| | P99| 346ms| 249ms | -97ms | -28.023
| getUserStatus | Avg| 1ms| 0s | -1ms | -160.176
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 5ms| 4ms | -1ms | -20.845
| | P99| 130ms| 95ms | -35ms | -26.931
| getUsers | Avg| 19ms| 16ms | -3ms | -15.446
| | P99| 286ms| 241ms | -45ms | -15.749
| getUsersByIds | Avg| 4ms| 3ms | -1ms | -26.267
| | P99| 66ms| 56ms | -10ms | -15.064
| getUsersByNames | Avg| 18ms| 16ms | -2ms | -11.001
| | P99| 221ms| 196ms | -25ms | -11.305
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 142ms| 38ms | -104ms | -73.037
| | P99| 249ms| 50ms | -199ms | -80.080
| listCPAFields | Avg| 22ms| 35ms | 13ms | 58.763
| | P99| 243ms| 99ms | -144ms | -59.351
| listCPAValues | Avg| 36ms| 0s | -36ms | -100.590
| | P99| 411ms| 0s | -411ms | -100.061
| listChannelBookmarksForChannel | Avg| 15ms| 13ms | -2ms | -13.495
| | P99| 207ms| 177ms | -30ms | -14.483
| login | Avg| 166ms| 156ms | -10ms | -6.008
| | P99| 1.26s| 985ms | -275ms | -21.827
| logout | Avg| 208ms| 131ms | -77ms | -36.976
| | P99| 3.2s| 481ms | -2.719s | -84.958
| patchPost | Avg| 176ms| 125ms | -51ms | -29.037
| | P99| 3.269s| 1.57s | -1.699s | -51.970
| removeUserCustomStatus | Avg| 373ms| 373ms | 0s | 0.000
| | P99| 1.973s| 1.969s | -4ms | -0.203
| root | Avg| 14ms| 16ms | 2ms | 14.243
| | P99| 203ms| 221ms | 18ms | 8.856
| saveReaction | Avg| 77ms| 69ms | -8ms | -10.326
| | P99| 647ms| 471ms | -176ms | -27.216
| searchAllChannels | Avg| 60ms| 56ms | -4ms | -6.648
| | P99| 407ms| 250ms | -157ms | -38.551
| searchGroupChannels | Avg| 22ms| 18ms | -4ms | -18.112
| | P99| 245ms| 199ms | -46ms | -18.761
| searchPostsInTeam | Avg| 329ms| 338ms | 9ms | 2.738
| | P99| 4.245s| 4.04s | -205ms | -4.829
| searchUsers | Avg| 63ms| 59ms | -4ms | -6.372
| | P99| 308ms| 248ms | -60ms | -19.459
| setPostReminder | Avg| 156ms| 118ms | -38ms | -24.346
| | P99| 1.78s| 872ms | -908ms | -51.007
| submitPerformanceReport | Avg| 1ms| 0s | -1ms | -197.164
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 79ms| 67ms | -12ms | -15.282
| | P99| 800ms| 565ms | -235ms | -29.371
| updateCategoriesForTeamForUser | Avg| 153ms| 189ms | 36ms | 23.605
| | P99| 1.728s| 1.878s | 150ms | 8.682
| updateChannelBookmark | Avg| 50ms| 36ms | -14ms | -28.057
| | P99| 463ms| 223ms | -240ms | -51.890
| updateChannelBookmarkSortOrder | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 49ms| 25ms | -24ms | -49.203
| updatePreferences | Avg| 47ms| 44ms | -3ms | -6.321
| | P99| 422ms| 394ms | -28ms | -6.642
| updateReadStateAllThreadsByUser | Avg| 15ms| 16ms | 1ms | 6.519
| | P99| 49ms| 96ms | 47ms | 95.756
| updateReadStateThreadByUser | Avg| 184ms| 153ms | -31ms | -16.821
| | P99| 2.032s| 1.414s | -618ms | -30.416
| updateUserCustomStatus | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 583ms| 589ms | 6ms | 1.030
| | P99| 2.335s| 2.308s | -27ms | -1.156
| upsertDraft | Avg| 20ms| 18ms | -2ms | -9.806
| | P99| 226ms| 212ms | -14ms | -6.193
| viewChannel | Avg| 85ms| 70ms | -15ms | -17.693
| | P99| 915ms| 750ms | -165ms | -18.036
