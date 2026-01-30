### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| LicenseStore.GetAll | avg | 5ms | 50ms | 45ms | 954.78
| ProductNoticesStore.GetViews | avg | 1ms | 11ms | 10ms | 687.49
| PostStore.AnalyticsPostCountByTeam | avg | 1ms | 9ms | 8ms | 643.20
| TeamStore.AnalyticsTeamCount | avg | 2ms | 9ms | 7ms | 429.47
| UserStore.GetProfilesInChannel | avg | 4ms | 17ms | 13ms | 309.01
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 3ms | 13ms | 10ms | 289.15
| LinkMetadataStore.Save | avg | 5ms | 18ms | 13ms | 259.14
| ChannelStore.GetMembers | avg | 12ms | 38ms | 26ms | 222.27
| CommandWebhookStore.Cleanup | avg | 10ms | 27ms | 17ms | 163.59
| ChannelBookmarkStore.Delete | avg | 8ms | 18ms | 10ms | 130.15
| UserStore.AnalyticsGetInactiveUsersCount | avg | 12ms | 27ms | 15ms | 129.88
| UserAccessTokenStore.GetByToken | avg | 8ms | 17ms | 9ms | 115.76
| ChannelStore.AnalyticsCountAll | avg | 20ms | 38ms | 18ms | 88.18
| ChannelStore.GetTeamChannels | avg | 32ms | 56ms | 24ms | 74.42
| EmojiStore.GetMultipleByName | avg | 4ms | 7ms | 3ms | 69.17
| UserStore.AnalyticsActiveCount | avg | 23ms | 36ms | 13ms | 57.71
| ThreadStore.MarkAllAsReadByTeam | avg | 15ms | 23ms | 8ms | 51.67
| TeamStore.GetActiveMemberCount | avg | 60ms | 85ms | 25ms | 41.49
| PostStore.GetPostsByIds | avg | 6ms | 8ms | 2ms | 34.05
| JobStore.UpdateStatusOptimistically | avg | 9ms | 12ms | 3ms | 33.79
| ChannelBookmarkStore.UpdateSortOrder | avg | 18ms | 24ms | 6ms | 33.35
| TokenStore.Cleanup | avg | 14ms | 18ms | 4ms | 27.78
| ChannelStore.UpdateSidebarCategories | avg | 49ms | 62ms | 13ms | 26.72
| TeamStore.GetTotalMemberCount | avg | 56ms | 71ms | 15ms | 26.59
| TemporaryPostStore.GetExpiredPosts | avg | 8ms | 10ms | 2ms | 24.02
| JobStore.Save | avg | 9ms | 11ms | 2ms | 22.23
| ChannelStore.GetChannelUnread | avg | 9ms | 11ms | 2ms | 21.24
| ChannelBookmarkStore.Get | avg | 9ms | 11ms | 2ms | 21.16
| ChannelStore.Save | avg | 32ms | 37ms | 5ms | 15.81
| UserStore.GetProfilesNotInChannel | avg | 13ms | 15ms | 2ms | 15.15
| ClusterDiscoveryStore.SetLastPingAt | avg | 14ms | 16ms | 2ms | 14.54
| ChannelBookmarkStore.Save | avg | 29ms | 33ms | 4ms | 13.81
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 18ms | 20ms | 2ms | 11.09
| ChannelStore.GetSidebarCategory | avg | 20ms | 22ms | 2ms | 9.98
| ChannelStore.Autocomplete | avg | 46ms | 50ms | 4ms | 8.61
| ChannelStore.GetPublicChannelsForTeam | avg | 25ms | 27ms | 2ms | 8.07
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 5ms | 95ms | 90ms | 1818.18
| LinkMetadataStore.Save | p99 | 75ms | 720ms | 645ms | 860.03
| ProductNoticesStore.GetViews | p99 | 5ms | 25ms | 20ms | 403.72
| ChannelBookmarkStore.UpdateSortOrder | p99 | 49ms | 243ms | 194ms | 395.78
| ChannelStore.GetMembers | p99 | 49ms | 239ms | 190ms | 386.44
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 24ms | 19ms | 383.84
| PostStore.AnalyticsPostCountByTeam | p99 | 5ms | 24ms | 19ms | 383.84
| UserAccessTokenStore.GetByToken | p99 | 87ms | 360ms | 273ms | 313.79
| LicenseStore.GetAll | p99 | 25ms | 99ms | 74ms | 300.99
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 25ms | 99ms | 74ms | 297.79
| ChannelStore.AnalyticsCountAll | p99 | 25ms | 98ms | 73ms | 293.76
| UserStore.GetProfilesInChannel | p99 | 24ms | 94ms | 70ms | 293.31
| UserStore.AnalyticsActiveCount | p99 | 25ms | 96ms | 71ms | 285.71
| ChannelBookmarkStore.Delete | p99 | 24ms | 93ms | 69ms | 284.54
| EmojiStore.GetMultipleByName | p99 | 24ms | 90ms | 66ms | 280.60
| ChannelStore.GetChannelsByIds | p99 | 10ms | 24ms | 14ms | 143.59
| TeamStore.GetMany | p99 | 10ms | 23ms | 13ms | 131.65
| ChannelStore.GetTeamChannels | p99 | 221ms | 445ms | 224ms | 101.13
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 10ms | 5ms | 101.01
| CommandWebhookStore.Cleanup | p99 | 49ms | 98ms | 49ms | 100.00
| PostStore.GetPostsByIds | p99 | 24ms | 48ms | 24ms | 98.36
| JobStore.UpdateStatusOptimistically | p99 | 50ms | 99ms | 49ms | 98.31
| TemporaryPostStore.GetExpiredPosts | p99 | 49ms | 94ms | 45ms | 92.15
| ChannelStore.GetPublicChannelsForTeam | p99 | 110ms | 210ms | 100ms | 91.15
| JobStore.UpdateStatus | p99 | 98ms | 172ms | 74ms | 75.32
| UserStore.GetMany | p99 | 50ms | 87ms | 37ms | 74.25
| ChannelBookmarkStore.Save | p99 | 231ms | 395ms | 164ms | 71.15
| ChannelStore.Save | p99 | 248ms | 417ms | 169ms | 68.07
| JobStore.GetNewestJobByStatusesAndType | p99 | 90ms | 143ms | 53ms | 58.75
| ChannelStore.GetChannelUnread | p99 | 95ms | 146ms | 51ms | 53.80
| PostAcknowledgementStore.GetForPost | p99 | 58ms | 85ms | 27ms | 46.28
| UserStore.GetByUsername | p99 | 140ms | 195ms | 55ms | 39.29
| FileInfoStore.Save | p99 | 114ms | 145ms | 31ms | 27.30
| ThreadStore.GetThreadUnreadReplyCount | p99 | 105ms | 133ms | 28ms | 26.73
| UserStore.UpdateUpdateAt | p99 | 50ms | 63ms | 13ms | 26.07
| FileInfoStore.AttachToPost | p99 | 135ms | 166ms | 31ms | 22.91
| SessionStore.Save | p99 | 103ms | 126ms | 23ms | 22.40
| DraftStore.GetDraftsForUser | p99 | 134ms | 160ms | 26ms | 19.37
| DraftStore.Upsert | p99 | 105ms | 125ms | 20ms | 19.12
| ChannelStore.GetMembersForUser | p99 | 112ms | 132ms | 20ms | 17.91
| PostPersistentNotificationStore.GetSingle | p99 | 63ms | 74ms | 11ms | 17.48
| PreferenceStore.Get | p99 | 111ms | 130ms | 19ms | 17.18
| StatusStore.SaveOrUpdateMany | p99 | 157ms | 183ms | 26ms | 16.54
| FileInfoStore.SetContent | p99 | 193ms | 223ms | 30ms | 15.57
| PostStore.GetEtag | p99 | 118ms | 136ms | 18ms | 15.24
| UserStore.AutocompleteUsersInChannel | p99 | 257ms | 296ms | 39ms | 15.19
| JobStore.Save | p99 | 86ms | 99ms | 13ms | 15.05
| UserStore.GetAllProfilesInChannel | p99 | 1.4s | 1.605s | 205ms | 14.64
| ChannelStore.GetAllChannelMembersForUser | p99 | 103ms | 117ms | 14ms | 13.58
| ChannelStore.Autocomplete | p99 | 231ms | 262ms | 31ms | 13.43
| ChannelStore.GetFileCount | p99 | 98ms | 111ms | 13ms | 13.33
| UserStore.GetProfilesByUsernames | p99 | 128ms | 144ms | 16ms | 12.52
| ChannelStore.GetPinnedPostCount | p99 | 96ms | 108ms | 12ms | 12.48
| StatusStore.GetByIds | p99 | 164ms | 184ms | 20ms | 12.19
| ChannelStore.UpdateSidebarCategories | p99 | 405ms | 453ms | 48ms | 11.85
| PostStore.GetPostsBefore | p99 | 130ms | 145ms | 15ms | 11.58
| SessionStore.GetLRUSessions | p99 | 70ms | 78ms | 8ms | 11.36
| FileInfoStore.Get | p99 | 118ms | 131ms | 13ms | 11.06
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 84ms | 93ms | 9ms | 10.72
| PostAcknowledgementStore.GetForPosts | p99 | 150ms | 166ms | 16ms | 10.65
| ThreadStore.GetThreadForUser | p99 | 172ms | 190ms | 18ms | 10.46
| ChannelStore.GetMemberForPost | p99 | 158ms | 174ms | 16ms | 10.10
| JobStore.GetCountByStatusAndType | p99 | 155ms | 170ms | 15ms | 9.65
| TeamStore.GetTotalMemberCount | p99 | 221ms | 242ms | 21ms | 9.48
| UserStore.GetUnreadCount | p99 | 86ms | 94ms | 8ms | 9.25
| ThreadStore.GetThreadFollowers | p99 | 77ms | 84ms | 7ms | 9.15
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 211ms | 230ms | 19ms | 9.02
| ThreadStore.GetThreadsForUser | p99 | 141ms | 153ms | 12ms | 8.52
| ChannelStore.GetSidebarCategory | p99 | 225ms | 244ms | 19ms | 8.44
| PostPriorityStore.GetForPosts | p99 | 160ms | 173ms | 13ms | 8.12
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 64ms | 69ms | 5ms | 7.79
| ChannelStore.GetChannels | p99 | 133ms | 143ms | 10ms | 7.54
| ChannelStore.Get | p99 | 175ms | 188ms | 13ms | 7.42
| ScheduledPostStore.CreateScheduledPost | p99 | 87ms | 93ms | 6ms | 6.92
| ThreadStore.MaintainMembership | p99 | 192ms | 205ms | 13ms | 6.76
| ReactionStore.GetForPost | p99 | 76ms | 81ms | 5ms | 6.56
| PostStore.Save | p99 | 245ms | 261ms | 16ms | 6.52
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 78ms | 83ms | 5ms | 6.43
| TeamStore.Get | p99 | 79ms | 84ms | 5ms | 6.30
| PostStore.GetSingle | p99 | 83ms | 88ms | 5ms | 5.99
| WebhookStore.GetOutgoingByTeam | p99 | 164ms | 173ms | 9ms | 5.48
| ThreadStore.MarkAsRead | p99 | 74ms | 78ms | 4ms | 5.41
| LinkMetadataStore.Get | p99 | 87ms | 91ms | 4ms | 4.58
| TeamStore.GetMember | p99 | 66ms | 69ms | 3ms | 4.53
| ThreadStore.MarkAllAsReadByChannels | p99 | 91ms | 95ms | 4ms | 4.40
| EmojiStore.GetByName | p99 | 91ms | 95ms | 4ms | 4.37
| ThreadStore.GetMembershipForUser | p99 | 94ms | 98ms | 4ms | 4.27
| ChannelStore.CreateDirectChannel | p99 | 411ms | 428ms | 17ms | 4.13
| PostStore.GetPostIdBeforeTime | p99 | 74ms | 77ms | 3ms | 4.06
| ChannelStore.UpdateLastViewedAt | p99 | 86ms | 89ms | 3ms | 3.48
| GroupStore.GetGroups | p99 | 87ms | 90ms | 3ms | 3.44
| ThreadStore.GetTotalUnreadMentions | p99 | 88ms | 91ms | 3ms | 3.43
| TeamStore.GetTeamsByUserId | p99 | 88ms | 91ms | 3ms | 3.40
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 91ms | 94ms | 3ms | 3.28
| ThreadStore.MarkAllAsReadByTeam | p99 | 96ms | 99ms | 3ms | 3.13
| RoleStore.GetByNames | p99 | 235ms | 242ms | 7ms | 2.98
| TeamStore.SaveMember | p99 | 209ms | 215ms | 6ms | 2.87
| UserStore.Update | p99 | 213ms | 219ms | 6ms | 2.82
| ChannelStore.SaveMember | p99 | 397ms | 408ms | 11ms | 2.77
| PostStore.Get | p99 | 228ms | 234ms | 6ms | 2.63
| SessionStore.UpdateLastActivityAt | p99 | 78ms | 80ms | 2ms | 2.57
| SystemStore.GetByName | p99 | 80ms | 82ms | 2ms | 2.49
| UserTermsOfServiceStore.GetByUser | p99 | 86ms | 88ms | 2ms | 2.33
| UserStore.GetForLogin | p99 | 87ms | 89ms | 2ms | 2.31
| ChannelStore.IncrementMentionCount | p99 | 89ms | 91ms | 2ms | 2.25
| PropertyFieldStore.SearchPropertyFields | p99 | 90ms | 92ms | 2ms | 2.22
| ChannelStore.GetByName | p99 | 94ms | 96ms | 2ms | 2.14
| ProductNoticesStore.View | p99 | 664ms | 678ms | 14ms | 2.11
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 95ms | 97ms | 2ms | 2.10
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 95ms | 97ms | 2ms | 2.10
| PostStore.GetPostsByThread | p99 | 96ms | 98ms | 2ms | 2.09
| StatusStore.Get | p99 | 96ms | 98ms | 2ms | 2.09
| SessionStore.Get | p99 | 193ms | 197ms | 4ms | 2.07
| UserStore.Get | p99 | 97ms | 99ms | 2ms | 2.06
| ChannelStore.CreateInitialSidebarCategories | p99 | 243ms | 248ms | 5ms | 2.06
| PostStore.GetPostsSince | p99 | 200ms | 204ms | 4ms | 2.00
| PreferenceStore.Save | p99 | 231ms | 235ms | 4ms | 1.73
| UserStore.GetProfileByIds | p99 | 134ms | 136ms | 2ms | 1.50
| PropertyValueStore.SearchPropertyValues | p99 | 134ms | 136ms | 2ms | 1.49
| ChannelStore.GetMemberCount | p99 | 202ms | 205ms | 3ms | 1.48
| DraftStore.Get | p99 | 157ms | 159ms | 2ms | 1.28
| TeamStore.GetActiveMemberCount | p99 | 240ms | 243ms | 3ms | 1.25
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 64ms | 0s | -64ms | -100.24
| JobStore.GetAllByTypePage | avg | 12ms | 2ms | -10ms | -85.76
| ChannelStore.CreateSidebarCategory | avg | 36ms | 10ms | -26ms | -71.24
| PostStore.AnalyticsPostCount | avg | 469ms | 221ms | -248ms | -52.88
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 8ms | 4ms | -4ms | -47.97
| PostStore.GetPostReminders | avg | 16ms | 9ms | -7ms | -43.98
| PostStore.GetPostReminderMetadata | avg | 12ms | 7ms | -5ms | -40.14
| BotStore.Get | avg | 8ms | 5ms | -3ms | -38.56
| PostPersistentNotificationStore.DeleteExpired | avg | 8ms | 5ms | -3ms | -38.49
| SessionStore.GetSessionsExpired | avg | 9ms | 6ms | -3ms | -33.30
| PreferenceStore.DeleteCategoryAndName | avg | 6ms | 4ms | -2ms | -31.86
| StatusStore.UpdateExpiredDNDStatuses | avg | 12ms | 9ms | -3ms | -25.50
| JobStore.UpdateOptimistically | avg | 8ms | 6ms | -2ms | -24.67
| PostStore.Delete | avg | 21ms | 16ms | -5ms | -23.71
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 15ms | 12ms | -3ms | -19.97
| SessionStore.Remove | avg | 11ms | 9ms | -2ms | -18.89
| JobStore.GetAllByStatus | avg | 14ms | 12ms | -2ms | -14.46
| ProductNoticesStore.ClearOldNotices | avg | 48ms | 42ms | -6ms | -12.40
| PostStore.SearchPostsForUser | avg | 161ms | 142ms | -19ms | -11.78
| PostStore.SetPostReminder | avg | 27ms | 24ms | -3ms | -11.17
| PostStore.Update | avg | 25ms | 23ms | -2ms | -8.15
| ChannelStore.AutocompleteInTeamForSearch | avg | 66ms | 61ms | -5ms | -7.58
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 243ms | 0s | -243ms | -100.20
| JobStore.GetAllByTypePage | p99 | 161ms | 5ms | -156ms | -96.60
| ChannelStore.CreateSidebarCategory | p99 | 235ms | 25ms | -210ms | -89.36
| PreferenceStore.DeleteCategoryAndName | p99 | 85ms | 24ms | -61ms | -71.77
| PostPersistentNotificationStore.DeleteExpired | p99 | 166ms | 47ms | -119ms | -71.68
| UserStore.GetProfilesNotInChannel | p99 | 222ms | 89ms | -133ms | -60.04
| PostStore.GetPostReminders | p99 | 199ms | 83ms | -116ms | -58.29
| PostStore.GetPostReminderMetadata | p99 | 186ms | 79ms | -107ms | -57.68
| StatusStore.UpdateExpiredDNDStatuses | p99 | 206ms | 91ms | -115ms | -55.76
| SessionStore.Remove | p99 | 373ms | 168ms | -205ms | -55.03
| PostStore.Delete | p99 | 205ms | 94ms | -111ms | -54.15
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 10ms | 5ms | -5ms | -50.25
| PostStore.AnalyticsPostCount | p99 | 990ms | 496ms | -494ms | -49.90
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 50ms | -49ms | -49.49
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 95ms | 48ms | -47ms | -49.47
| SessionStore.GetSessionsExpired | p99 | 93ms | 47ms | -46ms | -49.46
| BotStore.Get | p99 | 83ms | 42ms | -41ms | -49.10
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 83ms | 47ms | -36ms | -43.37
| JobStore.UpdateOptimistically | p99 | 98ms | 74ms | -24ms | -24.43
| ChannelStore.SearchGroupChannels | p99 | 169ms | 143ms | -26ms | -15.35
| ChannelStore.AutocompleteInTeamForSearch | p99 | 422ms | 371ms | -51ms | -12.08
| FileInfoStore.GetByIds | p99 | 100ms | 93ms | -7ms | -7.01
| PostStore.GetPostsAfter | p99 | 99ms | 93ms | -6ms | -6.03
| JobStore.GetAllByStatus | p99 | 194ms | 183ms | -11ms | -5.67
| ThreadStore.UpdateMembership | p99 | 78ms | 74ms | -4ms | -5.15
| ClusterDiscoveryStore.SetLastPingAt | p99 | 197ms | 187ms | -10ms | -5.06
| UserStore.IsEmpty | p99 | 43ms | 41ms | -2ms | -4.67
| UserStore.UpdateFailedPasswordAttempts | p99 | 87ms | 83ms | -4ms | -4.59
| PostStore.Update | p99 | 228ms | 218ms | -10ms | -4.39
| PostPersistentNotificationStore.Get | p99 | 157ms | 151ms | -6ms | -3.82
| PostStore.SearchPostsForUser | p99 | 2.313s | 2.226s | -87ms | -3.76
| ChannelStore.GetChannelsByUser | p99 | 89ms | 86ms | -3ms | -3.36
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 85ms | 83ms | -2ms | -2.35
| PostStore.SetPostReminder | p99 | 233ms | 228ms | -5ms | -2.14
| RoleStore.ChannelHigherScopedPermissions | p99 | 97ms | 95ms | -2ms | -2.07
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 0s | 6ms | 6ms | 3341.11
| updateChannelBookmark | avg | 12ms | 69ms | 57ms | 494.72
| getFilteredUsersStats | avg | 13ms | 48ms | 35ms | 260.72
| getPrevTrialLicense | avg | 7ms | 25ms | 18ms | 258.26
| getChannelMembers | avg | 12ms | 39ms | 27ms | 216.26
| getServerLimits | avg | 19ms | 51ms | 32ms | 165.98
| updateChannelBookmarkSortOrder | avg | 25ms | 48ms | 23ms | 93.22
| updateReadStateAllThreadsByUser | avg | 16ms | 29ms | 13ms | 83.44
| getRolesByNames | avg | 5ms | 8ms | 3ms | 58.56
| getTeamStats | avg | 64ms | 94ms | 30ms | 46.61
| logout | avg | 79ms | 114ms | 35ms | 44.53
| updateCategoriesForTeamForUser | avg | 94ms | 131ms | 37ms | 39.23
| createChannel | avg | 477ms | 606ms | 129ms | 27.03
| handleCheckCWSConnection | avg | 79ms | 99ms | 20ms | 25.20
| getChannelUnread | avg | 10ms | 12ms | 2ms | 19.19
| getChannel | avg | 17ms | 20ms | 3ms | 17.55
| deletePost | avg | 33ms | 38ms | 5ms | 15.25
| updatePreferences | avg | 26ms | 29ms | 3ms | 11.44
| patchPost | avg | 73ms | 80ms | 7ms | 9.61
| searchAllChannels | avg | 47ms | 51ms | 4ms | 8.47
| getPublicChannelsForTeam | avg | 26ms | 28ms | 2ms | 7.64
| createGroupChannel | avg | 702ms | 752ms | 50ms | 7.13
| getPostsForChannel | avg | 91ms | 97ms | 6ms | 6.58
| saveReaction | avg | 32ms | 34ms | 2ms | 6.17
| getPostThread | avg | 53ms | 56ms | 3ms | 5.67
| viewChannel | avg | 36ms | 38ms | 2ms | 5.51
| updateReadStateThreadByUser | avg | 110ms | 116ms | 6ms | 5.47
| addChannelMember | avg | 404ms | 422ms | 18ms | 4.46
| followThreadByUser | avg | 46ms | 48ms | 2ms | 4.32
| createPost | avg | 554ms | 566ms | 12ms | 2.17
| createDirectChannel | avg | 442ms | 447ms | 5ms | 1.13
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | p99 | 5ms | 98ms | 93ms | 1877.55
| updateChannelBookmark | p99 | 25ms | 480ms | 455ms | 1830.99
| updateChannelBookmarkSortOrder | p99 | 49ms | 244ms | 195ms | 395.80
| getRolesByNames | p99 | 10ms | 49ms | 39ms | 391.96
| getServerLimits | p99 | 50ms | 244ms | 194ms | 391.92
| getChannelMembers | p99 | 49ms | 239ms | 190ms | 386.44
| getFilteredUsersStats | p99 | 25ms | 99ms | 74ms | 297.79
| handleCheckCWSConnection | p99 | 100ms | 248ms | 148ms | 148.74
| getPrevTrialLicense | p99 | 25ms | 50ms | 25ms | 101.12
| updateCategoriesForTeamForUser | p99 | 481ms | 930ms | 449ms | 93.35
| createChannelBookmark | p99 | 243ms | 457ms | 214ms | 88.03
| getPublicChannelsForTeam | p99 | 113ms | 210ms | 97ms | 85.89
| getTeamStats | p99 | 240ms | 445ms | 205ms | 85.24
| getChannelUnread | p99 | 100ms | 167ms | 67ms | 67.12
| logout | p99 | 436ms | 725ms | 289ms | 66.25
| patchPost | p99 | 490ms | 711ms | 221ms | 45.09
| updatePreferences | p99 | 269ms | 341ms | 72ms | 26.74
| getChannel | p99 | 179ms | 223ms | 44ms | 24.55
| saveReaction | p99 | 248ms | 299ms | 51ms | 20.54
| searchAllChannels | p99 | 232ms | 275ms | 43ms | 18.54
| getChannelMembersForTeamForUser | p99 | 120ms | 142ms | 22ms | 18.30
| updateReadStateThreadByUser | p99 | 682ms | 802ms | 120ms | 17.61
| autocompleteUsers | p99 | 250ms | 293ms | 43ms | 17.22
| listChannelBookmarksForChannel | p99 | 103ms | 120ms | 17ms | 16.46
| addChannelMember | p99 | 2.108s | 2.441s | 333ms | 15.80
| getDrafts | p99 | 152ms | 175ms | 23ms | 15.15
| addTeamMember | p99 | 4.918s | 5.653s | 735ms | 14.95
| createPost | p99 | 3.012s | 3.433s | 421ms | 13.98
| getFileThumbnail | p99 | 260ms | 293ms | 33ms | 12.70
| getAllTeams | p99 | 101ms | 113ms | 12ms | 11.83
| getTeamMember | p99 | 96ms | 106ms | 10ms | 10.39
| getUsersByNames | p99 | 142ms | 156ms | 14ms | 9.83
| getFilePreview | p99 | 326ms | 356ms | 30ms | 9.19
| createChannel | p99 | 2.215s | 2.418s | 203ms | 9.17
| getUserStatusesByIds | p99 | 50ms | 54ms | 4ms | 8.05
| getChannelStats | p99 | 100ms | 108ms | 8ms | 8.02
| createDirectChannel | p99 | 2.067s | 2.227s | 160ms | 7.74
| getChannelsForTeamForUser | p99 | 142ms | 151ms | 9ms | 6.34
| createGroupChannel | p99 | 3.893s | 4.132s | 239ms | 6.14
| deletePost | p99 | 228ms | 241ms | 13ms | 5.71
| viewChannel | p99 | 389ms | 411ms | 22ms | 5.66
| getPostsForChannel | p99 | 904ms | 955ms | 51ms | 5.64
| getPostThread | p99 | 448ms | 471ms | 23ms | 5.13
| getThreadsForUser | p99 | 161ms | 169ms | 8ms | 4.98
| getUsersByIds | p99 | 41ms | 43ms | 2ms | 4.83
| getClientConfig | p99 | 217ms | 224ms | 7ms | 3.22
| updateReadStateAllThreadsByUser | p99 | 96ms | 99ms | 3ms | 3.13
| deleteDraft | p99 | 172ms | 176ms | 4ms | 2.33
| getTeamsForUser | p99 | 90ms | 92ms | 2ms | 2.22
| getChannelMembersForUser | p99 | 91ms | 93ms | 2ms | 2.19
| upsertDraft | p99 | 187ms | 191ms | 4ms | 2.14
| getUsers | p99 | 203ms | 206ms | 3ms | 1.48
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 78ms | 0s | -78ms | -100.61
| getJobsByType | avg | 12ms | 2ms | -10ms | -84.90
| createCategoryForTeamForUser | avg | 45ms | 12ms | -33ms | -73.65
| getUsersByGroupChannelIds | avg | 9ms | 4ms | -5ms | -56.46
| setPostReminder | avg | 87ms | 58ms | -29ms | -33.42
| createChannelBookmark | avg | 57ms | 50ms | -7ms | -12.29
| searchPostsInTeam | avg | 182ms | 166ms | -16ms | -8.79
| getProfileImage | avg | 76ms | 70ms | -6ms | -7.86
| autocompleteChannelsForTeamForSearch | avg | 66ms | 61ms | -5ms | -7.56
| deleteChannelBookmark | avg | 72ms | 68ms | -4ms | -5.56
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | p99 | 246ms | 0s | -246ms | -99.90
| getJobsByType | p99 | 161ms | 5ms | -156ms | -96.60
| createCategoryForTeamForUser | p99 | 235ms | 25ms | -210ms | -89.36
| setPostReminder | p99 | 780ms | 242ms | -538ms | -68.98
| getUsersByGroupChannelIds | p99 | 10ms | 5ms | -5ms | -50.25
| createSchedulePost | p99 | 130ms | 95ms | -35ms | -26.93
| removeUserCustomStatus | p99 | 1.265s | 995ms | -270ms | -21.35
| login | p99 | 1.167s | 998ms | -169ms | -14.48
| searchGroupChannels | p99 | 175ms | 155ms | -20ms | -11.44
| autocompleteChannelsForTeamForSearch | p99 | 422ms | 386ms | -36ms | -8.53
| unfollowThreadByUser | p99 | 409ms | 390ms | -19ms | -4.64
| searchPostsInTeam | p99 | 2.322s | 2.24s | -82ms | -3.53
| getChannelsForUser | p99 | 91ms | 88ms | -3ms | -3.31
| getTeamScheduledPosts | p99 | 186ms | 181ms | -5ms | -2.69
| getProfileImage | p99 | 471ms | 460ms | -11ms | -2.34
| getPostsForChannelAroundLastUnread | p99 | 389ms | 381ms | -8ms | -2.05
| listCPAValues | p99 | 148ms | 145ms | -3ms | -2.03
| getCategoriesForTeamForUser | p99 | 183ms | 180ms | -3ms | -1.64
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 85ms | 1ms | 1.195
| BotStore.Get |  Avg| 8ms| 5ms | -3ms | -38.563
| |  P99| 83ms| 42ms | -41ms | -49.102
| ChannelBookmarkStore.Delete |  Avg| 8ms| 18ms | 10ms | 130.146
| |  P99| 24ms| 93ms | 69ms | 284.538
| ChannelBookmarkStore.Get |  Avg| 9ms| 11ms | 2ms | 21.155
| |  P99| 93ms| 93ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 97ms | 2ms | 2.101
| ChannelBookmarkStore.Save |  Avg| 29ms| 33ms | 4ms | 13.809
| |  P99| 231ms| 395ms | 164ms | 71.150
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 18ms| 24ms | 6ms | 33.352
| |  P99| 49ms| 243ms | 194ms | 395.780
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 20ms| 38ms | 18ms | 88.177
| |  P99| 25ms| 98ms | 73ms | 293.763
| ChannelStore.Autocomplete |  Avg| 46ms| 50ms | 4ms | 8.612
| |  P99| 231ms| 262ms | 31ms | 13.433
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 66ms| 61ms | -5ms | -7.584
| |  P99| 422ms| 371ms | -51ms | -12.078
| ChannelStore.CreateDirectChannel |  Avg| 56ms| 55ms | -1ms | -1.802
| |  P99| 411ms| 428ms | 17ms | 4.135
| ChannelStore.CreateInitialSidebarCategories |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 243ms| 248ms | 5ms | 2.060
| ChannelStore.CreateSidebarCategory |  Avg| 36ms| 10ms | -26ms | -71.240
| |  P99| 235ms| 25ms | -210ms | -89.363
| ChannelStore.Get |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 175ms| 188ms | 13ms | 7.417
| ChannelStore.GetAllChannelMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 103ms| 117ms | 14ms | 13.584
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 20ms | 2ms | 11.095
| |  P99| 211ms| 230ms | 19ms | 9.023
| ChannelStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 94ms| 96ms | 2ms | 2.135
| ChannelStore.GetChannelUnread |  Avg| 9ms| 11ms | 2ms | 21.242
| |  P99| 95ms| 146ms | 51ms | 53.798
| ChannelStore.GetChannels |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 133ms| 143ms | 10ms | 7.539
| ChannelStore.GetChannelsByIds |  Avg| 4ms| 5ms | 1ms | 27.729
| |  P99| 10ms| 24ms | 14ms | 143.589
| ChannelStore.GetChannelsByUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 86ms | -3ms | -3.361
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 97ms | 2ms | 2.104
| ChannelStore.GetFileCount |  Avg| 10ms| 11ms | 1ms | 9.544
| |  P99| 98ms| 111ms | 13ms | 13.328
| ChannelStore.GetGuestCount |  Avg| 9ms| 10ms | 1ms | 10.531
| |  P99| 96ms| 97ms | 1ms | 1.044
| ChannelStore.GetMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 91ms | -1ms | -1.091
| ChannelStore.GetMemberCount |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 202ms| 205ms | 3ms | 1.482
| ChannelStore.GetMemberCountsByGroup |  Avg| 64ms| 0s | -64ms | -100.242
| |  P99| 243ms| 0s | -243ms | -100.204
| ChannelStore.GetMemberForPost |  Avg| 14ms| 15ms | 1ms | 6.972
| |  P99| 158ms| 174ms | 16ms | 10.097
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 83ms| 83ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 12ms| 38ms | 26ms | 222.269
| |  P99| 49ms| 239ms | 190ms | 386.441
| ChannelStore.GetMembersForUser |  Avg| 11ms| 12ms | 1ms | 8.974
| |  P99| 112ms| 132ms | 20ms | 17.908
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 3ms| 13ms | 10ms | 289.147
| |  P99| 5ms| 95ms | 90ms | 1818.182
| ChannelStore.GetMembersForUserWithPagination |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.113
| ChannelStore.GetPinnedPostCount |  Avg| 8ms| 9ms | 1ms | 11.848
| |  P99| 96ms| 108ms | 12ms | 12.484
| ChannelStore.GetPublicChannelsForTeam |  Avg| 25ms| 27ms | 2ms | 8.066
| |  P99| 110ms| 210ms | 100ms | 91.153
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 167ms| 167ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 20ms| 22ms | 2ms | 9.977
| |  P99| 225ms| 244ms | 19ms | 8.444
| ChannelStore.GetTeamChannels |  Avg| 32ms| 56ms | 24ms | 74.421
| |  P99| 221ms| 445ms | 224ms | 101.131
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 89ms| 91ms | 2ms | 2.248
| ChannelStore.Save |  Avg| 32ms| 37ms | 5ms | 15.809
| |  P99| 248ms| 417ms | 169ms | 68.069
| ChannelStore.SaveMember |  Avg| 48ms| 49ms | 1ms | 2.063
| |  P99| 397ms| 408ms | 11ms | 2.770
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 169ms| 143ms | -26ms | -15.349
| ChannelStore.UpdateLastViewedAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 89ms | 3ms | 3.478
| ChannelStore.UpdateSidebarCategories |  Avg| 49ms| 62ms | 13ms | 26.715
| |  P99| 405ms| 453ms | 48ms | 11.852
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 78ms| 83ms | 5ms | 6.432
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 14ms| 16ms | 2ms | 14.537
| |  P99| 197ms| 187ms | -10ms | -5.063
| CommandWebhookStore.Cleanup |  Avg| 10ms| 27ms | 17ms | 163.591
| |  P99| 49ms| 98ms | 49ms | 100.000
| DraftStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.021
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 15ms| 12ms | -3ms | -19.974
| |  P99| 95ms| 48ms | -47ms | -49.474
| DraftStore.Get |  Avg| 12ms| 13ms | 1ms | 8.183
| |  P99| 157ms| 159ms | 2ms | 1.276
| DraftStore.GetDraftsForUser |  Avg| 12ms| 13ms | 1ms | 8.068
| |  P99| 134ms| 160ms | 26ms | 19.369
| DraftStore.Upsert |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 105ms| 125ms | 20ms | 19.124
| EmojiStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 95ms | 4ms | 4.373
| EmojiStore.GetMultipleByName |  Avg| 4ms| 7ms | 3ms | 69.172
| |  P99| 24ms| 90ms | 66ms | 280.599
| FileInfoStore.AttachToPost |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 135ms| 166ms | 31ms | 22.908
| FileInfoStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 118ms| 131ms | 13ms | 11.056
| FileInfoStore.GetByIds |  Avg| 9ms| 8ms | -1ms | -10.754
| |  P99| 100ms| 93ms | -7ms | -7.007
| FileInfoStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -12.775
| |  P99| 91ms| 92ms | 1ms | 1.099
| FileInfoStore.Save |  Avg| 11ms| 12ms | 1ms | 8.798
| |  P99| 114ms| 145ms | 31ms | 27.305
| FileInfoStore.SetContent |  Avg| 16ms| 17ms | 1ms | 6.434
| |  P99| 193ms| 223ms | 30ms | 15.566
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 6ms | 1ms | 18.412
| |  P99| 64ms| 69ms | 5ms | 7.792
| GroupStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 86ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 90ms | 3ms | 3.445
| JobStore.GetAllByStatus |  Avg| 14ms| 12ms | -2ms | -14.462
| |  P99| 194ms| 183ms | -11ms | -5.665
| JobStore.GetAllByTypePage |  Avg| 12ms| 2ms | -10ms | -85.764
| |  P99| 161ms| 5ms | -156ms | -96.596
| JobStore.GetCountByStatusAndType |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 155ms| 170ms | 15ms | 9.646
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 9ms | 1ms | 11.858
| |  P99| 90ms| 143ms | 53ms | 58.749
| JobStore.Save |  Avg| 9ms| 11ms | 2ms | 22.228
| |  P99| 86ms| 99ms | 13ms | 15.051
| JobStore.UpdateOptimistically |  Avg| 8ms| 6ms | -2ms | -24.672
| |  P99| 98ms| 74ms | -24ms | -24.428
| JobStore.UpdateStatus |  Avg| 8ms| 9ms | 1ms | 12.161
| |  P99| 98ms| 172ms | 74ms | 75.315
| JobStore.UpdateStatusOptimistically |  Avg| 9ms| 12ms | 3ms | 33.786
| |  P99| 50ms| 99ms | 49ms | 98.313
| LicenseStore.GetAll |  Avg| 5ms| 50ms | 45ms | 954.781
| |  P99| 25ms| 99ms | 74ms | 300.988
| LinkMetadataStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 91ms | 4ms | 4.580
| LinkMetadataStore.Save |  Avg| 5ms| 18ms | 13ms | 259.142
| |  P99| 75ms| 720ms | 645ms | 860.033
| PostAcknowledgementStore.GetForPost |  Avg| 5ms| 6ms | 1ms | 18.988
| |  P99| 58ms| 85ms | 27ms | 46.284
| PostAcknowledgementStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 150ms| 166ms | 16ms | 10.651
| PostPersistentNotificationStore.DeleteExpired |  Avg| 8ms| 5ms | -3ms | -38.488
| |  P99| 166ms| 47ms | -119ms | -71.682
| PostPersistentNotificationStore.Get |  Avg| 7ms| 8ms | 1ms | 14.595
| |  P99| 157ms| 151ms | -6ms | -3.822
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 63ms| 74ms | 11ms | 17.481
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| PostPriorityStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 85ms| 86ms | 1ms | 1.174
| PostPriorityStore.GetForPosts |  Avg| 11ms| 12ms | 1ms | 8.800
| |  P99| 160ms| 173ms | 13ms | 8.120
| PostStore.AnalyticsPostCount |  Avg| 469ms| 221ms | -248ms | -52.878
| |  P99| 990ms| 496ms | -494ms | -49.899
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 9ms | 8ms | 643.200
| |  P99| 5ms| 24ms | 19ms | 383.838
| PostStore.Delete |  Avg| 21ms| 16ms | -5ms | -23.707
| |  P99| 205ms| 94ms | -111ms | -54.145
| PostStore.Get |  Avg| 23ms| 24ms | 1ms | 4.409
| |  P99| 228ms| 234ms | 6ms | 2.635
| PostStore.GetEtag |  Avg| 10ms| 11ms | 1ms | 9.528
| |  P99| 118ms| 136ms | 18ms | 15.241
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 52ms| 52ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 74ms| 77ms | 3ms | 4.061
| PostStore.GetPostReminderMetadata |  Avg| 12ms| 7ms | -5ms | -40.137
| |  P99| 186ms| 79ms | -107ms | -57.681
| PostStore.GetPostReminders |  Avg| 16ms| 9ms | -7ms | -43.976
| |  P99| 199ms| 83ms | -116ms | -58.291
| PostStore.GetPosts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.350
| PostStore.GetPostsAfter |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 93ms | -6ms | -6.031
| PostStore.GetPostsBefore |  Avg| 12ms| 13ms | 1ms | 8.289
| |  P99| 130ms| 145ms | 15ms | 11.580
| PostStore.GetPostsByIds |  Avg| 6ms| 8ms | 2ms | 34.047
| |  P99| 24ms| 48ms | 24ms | 98.362
| PostStore.GetPostsByThread |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 96ms| 98ms | 2ms | 2.091
| PostStore.GetPostsSince |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 200ms| 204ms | 4ms | 2.003
| PostStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 88ms | 5ms | 5.992
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 26ms| 27ms | 1ms | 3.892
| |  P99| 245ms| 261ms | 16ms | 6.523
| PostStore.SearchPostsForUser |  Avg| 161ms| 142ms | -19ms | -11.775
| |  P99| 2.313s| 2.226s | -87ms | -3.761
| PostStore.SetPostReminder |  Avg| 27ms| 24ms | -3ms | -11.170
| |  P99| 233ms| 228ms | -5ms | -2.141
| PostStore.Update |  Avg| 25ms| 23ms | -2ms | -8.151
| |  P99| 228ms| 218ms | -10ms | -4.385
| PreferenceStore.DeleteCategoryAndName |  Avg| 6ms| 4ms | -2ms | -31.856
| |  P99| 85ms| 24ms | -61ms | -71.766
| PreferenceStore.Get |  Avg| 10ms| 11ms | 1ms | 9.775
| |  P99| 111ms| 130ms | 19ms | 17.180
| PreferenceStore.GetAll |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 94ms| 94ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 231ms| 235ms | 4ms | 1.733
| ProductNoticesStore.ClearOldNotices |  Avg| 48ms| 42ms | -6ms | -12.401
| |  P99| 99ms| 50ms | -49ms | -49.495
| ProductNoticesStore.GetViews |  Avg| 1ms| 11ms | 10ms | 687.493
| |  P99| 5ms| 25ms | 20ms | 403.717
| ProductNoticesStore.View |  Avg| 63ms| 62ms | -1ms | -1.595
| |  P99| 664ms| 678ms | 14ms | 2.107
| PropertyFieldStore.SearchPropertyFields |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 90ms| 92ms | 2ms | 2.216
| PropertyValueStore.SearchPropertyValues |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 134ms| 136ms | 2ms | 1.495
| ReactionStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -12.497
| |  P99| 76ms| 81ms | 5ms | 6.562
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -72.195
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 18ms| 19ms | 1ms | 5.451
| |  P99| 97ms| 95ms | -2ms | -2.068
| RoleStore.GetByNames |  Avg| 36ms| 35ms | -1ms | -2.746
| |  P99| 235ms| 242ms | 7ms | 2.982
| ScheduledPostStore.CreateScheduledPost |  Avg| 10ms| 11ms | 1ms | 10.460
| |  P99| 87ms| 93ms | 6ms | 6.923
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 15ms| 14ms | -1ms | -6.617
| |  P99| 91ms| 94ms | 3ms | 3.279
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 85ms| 83ms | -2ms | -2.354
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 6ms| 7ms | 1ms | 15.587
| |  P99| 83ms| 47ms | -36ms | -43.373
| SessionStore.Get |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 193ms| 197ms | 4ms | 2.071
| SessionStore.GetLRUSessions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 78ms | 8ms | 11.364
| SessionStore.GetSessionsExpired |  Avg| 9ms| 6ms | -3ms | -33.296
| |  P99| 93ms| 47ms | -46ms | -49.462
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 7ms| 8ms | 1ms | 14.119
| |  P99| 84ms| 93ms | 9ms | 10.718
| SessionStore.Remove |  Avg| 11ms| 9ms | -2ms | -18.894
| |  P99| 373ms| 168ms | -205ms | -55.029
| SessionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 103ms| 126ms | 23ms | 22.397
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 78ms| 80ms | 2ms | 2.570
| StatusStore.Get |  Avg| 8ms| 9ms | 1ms | 11.773
| |  P99| 96ms| 98ms | 2ms | 2.087
| StatusStore.GetByIds |  Avg| 13ms| 14ms | 1ms | 7.552
| |  P99| 164ms| 184ms | 20ms | 12.186
| StatusStore.SaveOrUpdate |  Avg| 9ms| 10ms | 1ms | 10.763
| |  P99| 98ms| 99ms | 1ms | 1.025
| StatusStore.SaveOrUpdateMany |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 157ms| 183ms | 26ms | 16.542
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 12ms| 9ms | -3ms | -25.500
| |  P99| 206ms| 91ms | -115ms | -55.758
| StatusStore.UpdateLastActivityAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 80ms| 80ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 80ms| 82ms | 2ms | 2.490
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 9ms | 7ms | 429.469
| |  P99| 5ms| 24ms | 19ms | 383.838
| TeamStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 79ms| 84ms | 5ms | 6.301
| TeamStore.GetActiveMemberCount |  Avg| 60ms| 85ms | 25ms | 41.487
| |  P99| 240ms| 243ms | 3ms | 1.247
| TeamStore.GetAllPage |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.114
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 92ms | 1ms | 1.096
| TeamStore.GetMany |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 131.646
| TeamStore.GetMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 66ms| 69ms | 3ms | 4.534
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 8ms | 1ms | 13.662
| |  P99| 88ms| 91ms | 3ms | 3.401
| TeamStore.GetTeamsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 90ms | 1ms | 1.127
| TeamStore.GetTotalMemberCount |  Avg| 56ms| 71ms | 15ms | 26.594
| |  P99| 221ms| 242ms | 21ms | 9.481
| TeamStore.SaveMember |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 209ms| 215ms | 6ms | 2.866
| TemporaryPostStore.GetExpiredPosts |  Avg| 8ms| 10ms | 2ms | 24.020
| |  P99| 49ms| 94ms | 45ms | 92.150
| ThreadStore.Get |  Avg| 8ms| 9ms | 1ms | 13.212
| |  P99| 100ms| 99ms | -1ms | -1.000
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 9ms | 1ms | 12.545
| |  P99| 94ms| 98ms | 4ms | 4.273
| ThreadStore.GetTeamsUnreadForUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 118ms| 117ms | -1ms | -0.847
| ThreadStore.GetThreadFollowers |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 77ms| 84ms | 7ms | 9.148
| ThreadStore.GetThreadForUser |  Avg| 15ms| 16ms | 1ms | 6.724
| |  P99| 172ms| 190ms | 18ms | 10.460
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 17ms| 18ms | 1ms | 5.788
| |  P99| 105ms| 133ms | 28ms | 26.734
| ThreadStore.GetThreadsForUser |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 141ms| 153ms | 12ms | 8.516
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 7ms| 8ms | 1ms | 13.588
| |  P99| 88ms| 91ms | 3ms | 3.427
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 90ms | 1ms | 1.123
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 12ms| 13ms | 1ms | 8.201
| |  P99| 192ms| 205ms | 13ms | 6.760
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 8ms | 1ms | 15.018
| |  P99| 91ms| 95ms | 4ms | 4.402
| ThreadStore.MarkAllAsReadByTeam |  Avg| 15ms| 23ms | 8ms | 51.667
| |  P99| 96ms| 99ms | 3ms | 3.125
| ThreadStore.MarkAsRead |  Avg| 6ms| 7ms | 1ms | 15.595
| |  P99| 74ms| 78ms | 4ms | 5.407
| ThreadStore.UpdateMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 78ms| 74ms | -4ms | -5.151
| TokenStore.Cleanup |  Avg| 14ms| 18ms | 4ms | 27.778
| |  P99| 49ms| 49ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 17ms | 9ms | 115.764
| |  P99| 87ms| 360ms | 273ms | 313.787
| UserStore.AnalyticsActiveCount |  Avg| 23ms| 36ms | 13ms | 57.710
| |  P99| 25ms| 96ms | 71ms | 285.714
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 12ms| 27ms | 15ms | 129.876
| |  P99| 25ms| 99ms | 74ms | 297.787
| UserStore.AutocompleteUsersInChannel |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 257ms| 296ms | 39ms | 15.192
| UserStore.Count |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 159ms| 160ms | 1ms | 0.630
| UserStore.Get |  Avg| 8ms| 9ms | 1ms | 12.017
| |  P99| 97ms| 99ms | 2ms | 2.064
| UserStore.GetAllProfiles |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 71ms | -1ms | -1.384
| UserStore.GetAllProfilesInChannel |  Avg| 325ms| 326ms | 1ms | 0.308
| |  P99| 1.4s| 1.605s | 205ms | 14.641
| UserStore.GetByUsername |  Avg| 11ms| 12ms | 1ms | 8.760
| |  P99| 140ms| 195ms | 55ms | 39.286
| UserStore.GetForLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 89ms | 2ms | 2.309
| UserStore.GetMany |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 50ms| 87ms | 37ms | 74.247
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 8ms| 4ms | -4ms | -47.974
| |  P99| 10ms| 5ms | -5ms | -50.251
| UserStore.GetProfileByIds |  Avg| 10ms| 11ms | 1ms | 9.678
| |  P99| 134ms| 136ms | 2ms | 1.496
| UserStore.GetProfilesByUsernames |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 128ms| 144ms | 16ms | 12.516
| UserStore.GetProfilesInChannel |  Avg| 4ms| 17ms | 13ms | 309.008
| |  P99| 24ms| 94ms | 70ms | 293.314
| UserStore.GetProfilesNotInChannel |  Avg| 13ms| 15ms | 2ms | 15.149
| |  P99| 222ms| 89ms | -133ms | -60.044
| UserStore.GetUnreadCount |  Avg| 7ms| 8ms | 1ms | 14.401
| |  P99| 86ms| 94ms | 8ms | 9.254
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.674
| UserStore.Save |  Avg| 171ms| 172ms | 1ms | 0.584
| |  P99| 492ms| 496ms | 4ms | 0.813
| UserStore.Search |  Avg| 44ms| 44ms | 0s | 0.000
| |  P99| 227ms| 227ms | 0s | 0.000
| UserStore.Update |  Avg| 18ms| 19ms | 1ms | 5.594
| |  P99| 213ms| 219ms | 6ms | 2.817
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 83ms | -4ms | -4.594
| UserStore.UpdateLastLogin |  Avg| 6ms| 7ms | 1ms | 15.448
| |  P99| 57ms| 57ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 50ms| 63ms | 13ms | 26.070
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 88ms | 2ms | 2.325
| WebhookStore.GetOutgoingByTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 164ms| 173ms | 9ms | 5.481
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 404ms| 422ms | 18ms | 4.461
| | P99| 2.108s| 2.441s | 333ms | 15.799
| addTeamMember | Avg| 1.114s| 1.114s | 0s | 0.000
| | P99| 4.918s| 5.653s | 735ms | 14.945
| autocompleteChannelsForTeamForSearch | Avg| 66ms| 61ms | -5ms | -7.560
| | P99| 422ms| 386ms | -36ms | -8.525
| autocompleteUsers | Avg| 61ms| 61ms | 0s | 0.000
| | P99| 250ms| 293ms | 43ms | 17.222
| channelMemberCountsByGroup | Avg| 78ms| 0s | -78ms | -100.606
| | P99| 246ms| 0s | -246ms | -99.898
| createCategoryForTeamForUser | Avg| 45ms| 12ms | -33ms | -73.652
| | P99| 235ms| 25ms | -210ms | -89.363
| createChannel | Avg| 477ms| 606ms | 129ms | 27.027
| | P99| 2.215s| 2.418s | 203ms | 9.165
| createChannelBookmark | Avg| 57ms| 50ms | -7ms | -12.295
| | P99| 243ms| 457ms | 214ms | 88.030
| createDirectChannel | Avg| 442ms| 447ms | 5ms | 1.130
| | P99| 2.067s| 2.227s | 160ms | 7.742
| createGroupChannel | Avg| 702ms| 752ms | 50ms | 7.126
| | P99| 3.893s| 4.132s | 239ms | 6.139
| createPost | Avg| 554ms| 566ms | 12ms | 2.167
| | P99| 3.012s| 3.433s | 421ms | 13.979
| createSchedulePost | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 130ms| 95ms | -35ms | -26.926
| createUser | Avg| 368ms| 370ms | 2ms | 0.544
| | P99| 2.026s| 2.033s | 7ms | 0.345
| deleteChannelBookmark | Avg| 72ms| 68ms | -4ms | -5.559
| | P99| 245ms| 246ms | 1ms | 0.407
| deleteDraft | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 172ms| 176ms | 4ms | 2.331
| deletePost | Avg| 33ms| 38ms | 5ms | 15.247
| | P99| 228ms| 241ms | 13ms | 5.714
| followThreadByUser | Avg| 46ms| 48ms | 2ms | 4.316
| | P99| 434ms| 436ms | 2ms | 0.461
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 101ms| 113ms | 12ms | 11.830
| getCategoriesForTeamForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 183ms| 180ms | -3ms | -1.640
| getChannel | Avg| 17ms| 20ms | 3ms | 17.545
| | P99| 179ms| 223ms | 44ms | 24.549
| getChannelMember | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 209ms| 210ms | 1ms | 0.479
| getChannelMembers | Avg| 12ms| 39ms | 27ms | 216.261
| | P99| 49ms| 239ms | 190ms | 386.441
| getChannelMembersForTeamForUser | Avg| 11ms| 12ms | 1ms | 8.792
| | P99| 120ms| 142ms | 22ms | 18.304
| getChannelMembersForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 91ms| 93ms | 2ms | 2.192
| getChannelStats | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 100ms| 108ms | 8ms | 8.021
| getChannelUnread | Avg| 10ms| 12ms | 2ms | 19.192
| | P99| 100ms| 167ms | 67ms | 67.120
| getChannelsForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 142ms| 151ms | 9ms | 6.336
| getChannelsForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 91ms| 88ms | -3ms | -3.314
| getClientConfig | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 217ms| 224ms | 7ms | 3.220
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 13ms| 14ms | 1ms | 7.592
| | P99| 152ms| 175ms | 23ms | 15.147
| getFilePreview | Avg| 64ms| 65ms | 1ms | 1.572
| | P99| 326ms| 356ms | 30ms | 9.188
| getFileThumbnail | Avg| 60ms| 60ms | 0s | 0.000
| | P99| 260ms| 293ms | 33ms | 12.695
| getFilteredUsersStats | Avg| 13ms| 48ms | 35ms | 260.724
| | P99| 25ms| 99ms | 74ms | 297.787
| getJobsByType | Avg| 12ms| 2ms | -10ms | -84.902
| | P99| 161ms| 5ms | -156ms | -96.596
| getPostThread | Avg| 53ms| 56ms | 3ms | 5.671
| | P99| 448ms| 471ms | 23ms | 5.128
| getPostsForChannel | Avg| 91ms| 97ms | 6ms | 6.578
| | P99| 904ms| 955ms | 51ms | 5.644
| getPostsForChannelAroundLastUnread | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 389ms| 381ms | -8ms | -2.055
| getPreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 96ms| 96ms | 0s | 0.000
| getPrevTrialLicense | Avg| 7ms| 25ms | 18ms | 258.262
| | P99| 25ms| 50ms | 25ms | 101.117
| getProfileImage | Avg| 76ms| 70ms | -6ms | -7.861
| | P99| 471ms| 460ms | -11ms | -2.337
| getPublicChannelsForTeam | Avg| 26ms| 28ms | 2ms | 7.639
| | P99| 113ms| 210ms | 97ms | 85.885
| getRolesByNames | Avg| 5ms| 8ms | 3ms | 58.555
| | P99| 10ms| 49ms | 39ms | 391.960
| getServerLimits | Avg| 19ms| 51ms | 32ms | 165.976
| | P99| 50ms| 244ms | 194ms | 391.919
| getTeamMember | Avg| 8ms| 9ms | 1ms | 12.395
| | P99| 96ms| 106ms | 10ms | 10.392
| getTeamMembersForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 97ms| 98ms | 1ms | 1.034
| getTeamScheduledPosts | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 186ms| 181ms | -5ms | -2.694
| getTeamStats | Avg| 64ms| 94ms | 30ms | 46.611
| | P99| 240ms| 445ms | 205ms | 85.240
| getTeamsForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 90ms| 92ms | 2ms | 2.216
| getTeamsUnreadForUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 201ms| 200ms | -1ms | -0.498
| getThreadsForUser | Avg| 13ms| 14ms | 1ms | 7.494
| | P99| 161ms| 169ms | 8ms | 4.984
| getUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 215ms| 214ms | -1ms | -0.465
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 50ms| 54ms | 4ms | 8.053
| getUsers | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 203ms| 206ms | 3ms | 1.476
| getUsersByGroupChannelIds | Avg| 9ms| 4ms | -5ms | -56.459
| | P99| 10ms| 5ms | -5ms | -50.251
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 41ms| 43ms | 2ms | 4.826
| getUsersByNames | Avg| 12ms| 13ms | 1ms | 8.259
| | P99| 142ms| 156ms | 14ms | 9.833
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 79ms| 99ms | 20ms | 25.204
| | P99| 100ms| 248ms | 148ms | 148.744
| listCPAFields | Avg| 8ms| 9ms | 1ms | 11.949
| | P99| 99ms| 100ms | 1ms | 1.010
| listCPAValues | Avg| 12ms| 11ms | -1ms | -8.616
| | P99| 148ms| 145ms | -3ms | -2.032
| listChannelBookmarksForChannel | Avg| 9ms| 10ms | 1ms | 11.053
| | P99| 103ms| 120ms | 17ms | 16.463
| login | Avg| 172ms| 171ms | -1ms | -0.583
| | P99| 1.167s| 998ms | -169ms | -14.481
| logout | Avg| 79ms| 114ms | 35ms | 44.529
| | P99| 436ms| 725ms | 289ms | 66.246
| patchPost | Avg| 73ms| 80ms | 7ms | 9.606
| | P99| 490ms| 711ms | 221ms | 45.086
| removeUserCustomStatus | Avg| 297ms| 299ms | 2ms | 0.673
| | P99| 1.265s| 995ms | -270ms | -21.345
| root | Avg| 0s| 6ms | 6ms | 3341.109
| | P99| 5ms| 98ms | 93ms | 1877.548
| saveReaction | Avg| 32ms| 34ms | 2ms | 6.166
| | P99| 248ms| 299ms | 51ms | 20.543
| searchAllChannels | Avg| 47ms| 51ms | 4ms | 8.474
| | P99| 232ms| 275ms | 43ms | 18.542
| searchGroupChannels | Avg| 15ms| 14ms | -1ms | -6.794
| | P99| 175ms| 155ms | -20ms | -11.444
| searchPostsInTeam | Avg| 182ms| 166ms | -16ms | -8.794
| | P99| 2.322s| 2.24s | -82ms | -3.532
| searchUsers | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 230ms| 230ms | 0s | 0.000
| setPostReminder | Avg| 87ms| 58ms | -29ms | -33.419
| | P99| 780ms| 242ms | -538ms | -68.977
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 44ms| 43ms | -1ms | -2.294
| | P99| 409ms| 390ms | -19ms | -4.641
| updateCategoriesForTeamForUser | Avg| 94ms| 131ms | 37ms | 39.232
| | P99| 481ms| 930ms | 449ms | 93.347
| updateChannelBookmark | Avg| 12ms| 69ms | 57ms | 494.724
| | P99| 25ms| 480ms | 455ms | 1830.986
| updateChannelBookmarkSortOrder | Avg| 25ms| 48ms | 23ms | 93.222
| | P99| 49ms| 244ms | 195ms | 395.799
| updatePreferences | Avg| 26ms| 29ms | 3ms | 11.438
| | P99| 269ms| 341ms | 72ms | 26.739
| updateReadStateAllThreadsByUser | Avg| 16ms| 29ms | 13ms | 83.443
| | P99| 96ms| 99ms | 3ms | 3.125
| updateReadStateThreadByUser | Avg| 110ms| 116ms | 6ms | 5.473
| | P99| 682ms| 802ms | 120ms | 17.606
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 508ms| 510ms | 2ms | 0.394
| | P99| 2.052s| 2.053s | 1ms | 0.049
| upsertDraft | Avg| 14ms| 15ms | 1ms | 7.137
| | P99| 187ms| 191ms | 4ms | 2.143
| viewChannel | Avg| 36ms| 38ms | 2ms | 5.508
| | P99| 389ms| 411ms | 22ms | 5.661
