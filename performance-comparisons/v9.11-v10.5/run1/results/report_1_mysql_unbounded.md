### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | avg | 48ms | 107ms | 59ms | 122.65
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 14ms | 27ms | 13ms | 89.67
| ChannelStore.Save | avg | 14ms | 22ms | 8ms | 55.52
| ChannelStore.GetAllChannelMembersForUser | avg | 5ms | 7ms | 2ms | 42.12
| PostStore.GetPosts | avg | 6ms | 8ms | 2ms | 34.54
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | p99 | 380ms | 455ms | 75ms | 19.75
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 2ms | 0s | -2ms | -121.88
| CommandWebhookStore.Cleanup | avg | 2ms | 0s | -2ms | -120.68
| TokenStore.Cleanup | avg | 2ms | 0s | -2ms | -118.70
| PreferenceStore.DeleteCategoryAndName | avg | 3ms | 0s | -3ms | -114.53
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 3ms | 0s | -3ms | -110.56
| ScheduledPostStore.CreateScheduledPost | avg | 6ms | 0s | -6ms | -108.23
| ChannelStore.IsReadOnlyChannel | avg | 2ms | 0s | -2ms | -106.63
| ChannelBookmarkStore.Delete | avg | 6ms | 0s | -6ms | -106.43
| EmojiStore.GetMultipleByName | avg | 2ms | 0s | -2ms | -104.47
| ScheduledPostStore.GetPendingScheduledPosts | avg | 7ms | 0s | -7ms | -104.42
| SharedChannelStore.HasChannel | avg | 3ms | 0s | -3ms | -104.32
| ProductNoticesStore.ClearOldNotices | avg | 2ms | 0s | -2ms | -102.77
| RoleStore.GetByNames | avg | 12ms | 0s | -12ms | -102.43
| ChannelStore.CreateSidebarCategory | avg | 18ms | 0s | -18ms | -102.18
| ChannelStore.GetTeamChannels | avg | 25ms | 0s | -25ms | -101.78
| PostStore.Delete | avg | 14ms | 0s | -14ms | -100.83
| ScheduledPostStore.GetScheduledPostsForUser | avg | 4ms | 0s | -4ms | -100.44
| PostStore.AnalyticsPostCount | avg | 822ms | 0s | -822ms | -100.01
| TeamStore.GetTotalMemberCount | avg | 108ms | 0s | -108ms | -99.99
| TeamStore.GetActiveMemberCount | avg | 139ms | 0s | -139ms | -99.86
| ChannelStore.UpdateSidebarCategories | avg | 30ms | 0s | -30ms | -99.45
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -99.27
| ChannelStore.GetSidebarCategory | avg | 6ms | 0s | -6ms | -98.54
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 22ms | 0s | -22ms | -98.29
| SessionStore.Remove | avg | 5ms | 0s | -5ms | -97.63
| PostStore.SetPostReminder | avg | 8ms | 0s | -8ms | -97.32
| ChannelBookmarkStore.Save | avg | 9ms | 0s | -9ms | -96.21
| UserStore.GetProfilesNotInChannel | avg | 5ms | 0s | -5ms | -95.05
| UserStore.GetProfilesInChannel | avg | 2ms | 0s | -2ms | -88.12
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 0s | -2ms | -87.87
| UserAccessTokenStore.GetByToken | avg | 2ms | 0s | -2ms | -86.06
| UserStore.IsEmpty | avg | 3ms | 1ms | -2ms | -74.70
| SessionStore.GetSessionsExpired | avg | 8ms | 2ms | -6ms | -72.64
| WebhookStore.GetOutgoingByTeam | avg | 7ms | 2ms | -5ms | -71.24
| JobStore.GetCountByStatusAndType | avg | 6ms | 2ms | -4ms | -66.28
| UserStore.GetForLogin | avg | 5ms | 2ms | -3ms | -65.13
| PluginStore.List | avg | 5ms | 2ms | -3ms | -65.09
| PostStore.GetEtag | avg | 5ms | 2ms | -3ms | -64.01
| ThreadStore.GetTeamsUnreadForUser | avg | 5ms | 2ms | -3ms | -63.97
| PostAcknowledgementStore.GetForPosts | avg | 5ms | 2ms | -3ms | -63.20
| ChannelStore.Get | avg | 5ms | 2ms | -3ms | -62.41
| GroupStore.GetByName | avg | 5ms | 2ms | -3ms | -61.77
| PostPriorityStore.GetForPosts | avg | 5ms | 2ms | -3ms | -61.54
| ChannelStore.GetGuestCount | avg | 5ms | 2ms | -3ms | -57.48
| PostStore.GetPostsSince | avg | 12ms | 5ms | -7ms | -57.30
| ChannelStore.GetFileCount | avg | 5ms | 2ms | -3ms | -57.10
| ChannelStore.GetMemberForPost | avg | 4ms | 2ms | -2ms | -55.97
| PreferenceStore.Get | avg | 4ms | 2ms | -2ms | -55.53
| PreferenceStore.GetAll | avg | 5ms | 2ms | -3ms | -55.19
| ChannelStore.GetByName | avg | 7ms | 3ms | -4ms | -54.87
| UserStore.GetProfilesByUsernames | avg | 4ms | 2ms | -2ms | -53.22
| JobStore.GetNewestJobByStatusesAndType | avg | 6ms | 3ms | -3ms | -52.61
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 4ms | 2ms | -2ms | -52.59
| UserStore.Count | avg | 105ms | 50ms | -55ms | -52.58
| GroupStore.GetGroups | avg | 4ms | 2ms | -2ms | -52.51
| StatusStore.Get | avg | 4ms | 2ms | -2ms | -52.35
| JobStore.UpdateStatusOptimistically | avg | 8ms | 4ms | -4ms | -52.12
| SessionStore.Get | avg | 8ms | 4ms | -4ms | -52.07
| DraftStore.GetDraftsForUser | avg | 4ms | 2ms | -2ms | -51.91
| PostPriorityStore.GetForPost | avg | 4ms | 2ms | -2ms | -51.69
| ChannelStore.GetMemberLastViewedAt | avg | 4ms | 2ms | -2ms | -50.70
| UserStore.GetMany | avg | 4ms | 2ms | -2ms | -50.25
| PostAcknowledgementStore.GetForPost | avg | 4ms | 2ms | -2ms | -50.20
| UserStore.GetAllProfilesInChannel | avg | 356ms | 178ms | -178ms | -49.99
| ThreadStore.GetTotalThreads | avg | 4ms | 2ms | -2ms | -49.82
| ThreadStore.GetTotalUnreadThreads | avg | 4ms | 2ms | -2ms | -49.69
| ThreadStore.GetTotalUnreadMentions | avg | 4ms | 2ms | -2ms | -49.67
| ChannelStore.SearchGroupChannels | avg | 4ms | 2ms | -2ms | -49.50
| JobStore.GetAllByStatus | avg | 4ms | 2ms | -2ms | -49.21
| ChannelStore.GetChannels | avg | 4ms | 2ms | -2ms | -49.17
| SessionStore.GetLRUSessions | avg | 4ms | 2ms | -2ms | -49.11
| TeamStore.GetTeamsForUser | avg | 4ms | 2ms | -2ms | -48.60
| ChannelStore.GetChannelsByUser | avg | 4ms | 2ms | -2ms | -48.58
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 4ms | 2ms | -2ms | -48.29
| TeamStore.GetChannelUnreadsForAllTeams | avg | 4ms | 2ms | -2ms | -47.57
| UserTermsOfServiceStore.GetByUser | avg | 4ms | 2ms | -2ms | -46.84
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 13ms | 7ms | -6ms | -46.70
| TeamStore.GetAllPage | avg | 4ms | 2ms | -2ms | -46.56
| ChannelStore.GetMemberCount | avg | 105ms | 57ms | -48ms | -45.57
| TeamStore.GetTeamsByUserId | avg | 4ms | 2ms | -2ms | -45.54
| UserStore.GetAllProfiles | avg | 5ms | 3ms | -2ms | -44.29
| ChannelStore.GetMembersForUserWithPagination | avg | 5ms | 3ms | -2ms | -41.70
| PostStore.GetPostsBefore | avg | 5ms | 3ms | -2ms | -41.44
| ClusterDiscoveryStore.SetLastPingAt | avg | 5ms | 3ms | -2ms | -40.88
| UserStore.GetUnreadCount | avg | 5ms | 3ms | -2ms | -37.02
| UserStore.Update | avg | 8ms | 5ms | -3ms | -36.52
| UserStore.AutocompleteUsersInChannel | avg | 180ms | 115ms | -65ms | -36.02
| ChannelStore.SaveMember | avg | 36ms | 24ms | -12ms | -33.69
| ProductNoticesStore.View | avg | 38ms | 26ms | -12ms | -31.87
| PostStore.Get | avg | 7ms | 5ms | -2ms | -30.15
| SessionStore.Save | avg | 8ms | 6ms | -2ms | -24.73
| PostStore.GetPostReminders | avg | 8ms | 6ms | -2ms | -24.10
| FileInfoStore.SetContent | avg | 9ms | 7ms | -2ms | -23.20
| ChannelStore.AutocompleteInTeamForSearch | avg | 156ms | 121ms | -35ms | -22.37
| ChannelStore.CreateInitialSidebarCategories | avg | 23ms | 18ms | -5ms | -21.72
| TeamStore.SaveMember | avg | 80ms | 64ms | -16ms | -20.12
| PreferenceStore.Save | avg | 11ms | 9ms | -2ms | -18.12
| ChannelStore.CreateDirectChannel | avg | 24ms | 20ms | -4ms | -16.75
| UserStore.Save | avg | 79ms | 67ms | -12ms | -15.22
| PostStore.Save | avg | 13ms | 11ms | -2ms | -14.87
| UserStore.Search | avg | 45ms | 40ms | -5ms | -11.00
| ChannelStore.Autocomplete | avg | 1.019s | 914ms | -105ms | -10.30
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SharedChannelStore.HasChannel | p99 | 27ms | 0s | -27ms | -101.76
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 0s | -10ms | -101.14
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.GetMultipleByName | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.GetMaxMessageSize | p99 | 5ms | 0s | -5ms | -101.01
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -101.01
| CommandWebhookStore.Cleanup | p99 | 5ms | 0s | -5ms | -101.00
| TokenStore.Cleanup | p99 | 5ms | 0s | -5ms | -101.00
| UserStore.GetProfilesInChannel | p99 | 5ms | 0s | -5ms | -101.00
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -100.96
| ChannelStore.IsReadOnlyChannel | p99 | 23ms | 0s | -23ms | -100.79
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -100.67
| ChannelStore.GetSidebarCategory | p99 | 77ms | 0s | -77ms | -100.65
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| PostStore.Delete | p99 | 25ms | 0s | -25ms | -100.60
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 93ms | 0s | -93ms | -100.54
| ChannelStore.GetTeamChannels | p99 | 48ms | 0s | -48ms | -100.50
| TeamStore.GetActiveMemberCount | p99 | 249ms | 0s | -249ms | -100.20
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 87ms | 0s | -87ms | -100.00
| PostStore.AnalyticsPostCount | p99 | 995ms | 0s | -995ms | -100.00
| PostStore.SetPostReminder | p99 | 44ms | 0s | -44ms | -99.99
| ScheduledPostStore.CreateScheduledPost | p99 | 40ms | 0s | -40ms | -99.99
| TeamStore.GetTotalMemberCount | p99 | 247ms | 0s | -247ms | -99.88
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 23ms | 0s | -23ms | -99.78
| ChannelStore.UpdateSidebarCategories | p99 | 179ms | 0s | -179ms | -99.73
| SessionStore.Remove | p99 | 23ms | 0s | -23ms | -99.46
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 48ms | 0s | -48ms | -98.97
| ChannelBookmarkStore.Save | p99 | 24ms | 0s | -24ms | -98.01
| PreferenceStore.DeleteCategoryAndName | p99 | 9ms | 0s | -9ms | -97.30
| JobStore.GetCountByStatusAndType | p99 | 141ms | 5ms | -136ms | -96.80
| SessionStore.GetSessionsExpired | p99 | 95ms | 5ms | -90ms | -95.24
| UserAccessTokenStore.GetByToken | p99 | 8ms | 0s | -8ms | -94.68
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 166ms | 10ms | -156ms | -94.24
| JobStore.GetNewestJobByStatusesAndType | p99 | 92ms | 5ms | -87ms | -94.22
| PreferenceStore.GetAll | p99 | 79ms | 5ms | -74ms | -94.14
| UserStore.GetMany | p99 | 76ms | 5ms | -71ms | -94.03
| WebhookStore.GetOutgoingByTeam | p99 | 70ms | 5ms | -65ms | -93.45
| PluginStore.List | p99 | 74ms | 5ms | -69ms | -93.25
| ChannelStore.Get | p99 | 77ms | 5ms | -72ms | -93.24
| GroupStore.GetByName | p99 | 77ms | 5ms | -72ms | -93.10
| UserStore.GetForLogin | p99 | 67ms | 5ms | -62ms | -93.08
| ThreadStore.GetTeamsUnreadForUser | p99 | 61ms | 5ms | -56ms | -92.51
| SessionStore.GetLRUSessions | p99 | 62ms | 5ms | -57ms | -92.43
| UserTermsOfServiceStore.GetByUser | p99 | 66ms | 5ms | -61ms | -92.34
| ChannelStore.GetGuestCount | p99 | 76ms | 6ms | -70ms | -92.15
| JobStore.UpdateOptimistically | p99 | 64ms | 5ms | -59ms | -91.47
| TeamStore.GetAllPage | p99 | 57ms | 5ms | -52ms | -91.46
| PostAcknowledgementStore.GetForPost | p99 | 57ms | 5ms | -52ms | -91.22
| TeamStore.GetTeamsByUserId | p99 | 58ms | 5ms | -53ms | -91.14
| TeamStore.GetTeamsForUser | p99 | 51ms | 5ms | -46ms | -90.80
| ThreadStore.GetTotalUnreadThreads | p99 | 50ms | 5ms | -45ms | -90.52
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 53ms | 5ms | -48ms | -90.05
| JobStore.GetAllByStatus | p99 | 48ms | 5ms | -43ms | -89.68
| ChannelStore.GetMembersForUserWithPagination | p99 | 50ms | 5ms | -45ms | -89.66
| ThreadStore.GetTotalUnreadMentions | p99 | 48ms | 5ms | -43ms | -89.58
| RoleStore.GetByNames | p99 | 48ms | 5ms | -43ms | -89.44
| ThreadStore.GetThreadsForUser | p99 | 47ms | 5ms | -42ms | -89.40
| PostStore.GetEtag | p99 | 67ms | 7ms | -60ms | -89.39
| PostStore.GetPostsBefore | p99 | 46ms | 5ms | -41ms | -89.21
| ChannelStore.GetMemberLastViewedAt | p99 | 49ms | 5ms | -44ms | -89.12
| ThreadStore.GetTotalThreads | p99 | 49ms | 5ms | -44ms | -89.06
| UserStore.GetProfilesByUsernames | p99 | 42ms | 5ms | -37ms | -88.98
| ChannelStore.SearchGroupChannels | p99 | 45ms | 5ms | -40ms | -88.92
| ClusterDiscoveryStore.SetLastPingAt | p99 | 46ms | 5ms | -41ms | -88.89
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 49ms | 5ms | -44ms | -88.89
| ChannelStore.GetChannels | p99 | 47ms | 5ms | -42ms | -88.73
| PreferenceStore.Get | p99 | 42ms | 5ms | -37ms | -88.72
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 48ms | 5ms | -43ms | -88.67
| ChannelStore.GetByName | p99 | 78ms | 9ms | -69ms | -88.66
| PostStore.GetPostReminders | p99 | 87ms | 10ms | -77ms | -88.51
| SessionStore.Get | p99 | 85ms | 10ms | -75ms | -88.45
| ChannelStore.GetMembersForUser | p99 | 44ms | 5ms | -39ms | -88.31
| StatusStore.Get | p99 | 48ms | 6ms | -42ms | -88.26
| UserStore.GetAllProfiles | p99 | 45ms | 5ms | -40ms | -88.12
| DraftStore.GetDraftsForUser | p99 | 44ms | 5ms | -39ms | -88.11
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.052s | 247ms | -1.805s | -87.98
| UserStore.GetByUsername | p99 | 39ms | 5ms | -34ms | -87.94
| ChannelStore.GetFileCount | p99 | 44ms | 5ms | -39ms | -87.91
| PostPriorityStore.GetForPost | p99 | 42ms | 5ms | -37ms | -87.78
| ThreadStore.GetThreadFollowers | p99 | 42ms | 5ms | -37ms | -87.75
| PostPersistentNotificationStore.GetSingle | p99 | 38ms | 5ms | -33ms | -87.74
| UserStore.IsEmpty | p99 | 42ms | 5ms | -37ms | -87.24
| DraftStore.Get | p99 | 40ms | 5ms | -35ms | -87.13
| UserStore.GetProfileByIds | p99 | 39ms | 5ms | -34ms | -86.93
| FileInfoStore.Save | p99 | 35ms | 5ms | -30ms | -86.64
| ChannelStore.GetMemberForPost | p99 | 40ms | 5ms | -35ms | -86.59
| EmojiStore.GetByName | p99 | 33ms | 5ms | -28ms | -85.36
| UserStore.Update | p99 | 66ms | 10ms | -56ms | -85.16
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 33ms | 5ms | -28ms | -84.73
| ThreadStore.GetMembershipForUser | p99 | 32ms | 5ms | -27ms | -84.42
| TeamStore.GetMember | p99 | 32ms | 5ms | -27ms | -84.34
| DraftStore.Upsert | p99 | 31ms | 5ms | -26ms | -84.12
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 29ms | 5ms | -24ms | -84.08
| FileInfoStore.Get | p99 | 29ms | 5ms | -24ms | -83.63
| ChannelStore.GetMember | p99 | 30ms | 5ms | -25ms | -83.11
| StatusStore.GetByIds | p99 | 27ms | 5ms | -22ms | -82.97
| PostStore.Get | p99 | 58ms | 10ms | -48ms | -82.15
| SessionStore.Save | p99 | 72ms | 13ms | -59ms | -81.82
| PostPriorityStore.GetForPosts | p99 | 46ms | 9ms | -37ms | -81.25
| UserStore.Get | p99 | 25ms | 5ms | -20ms | -81.17
| GroupStore.GetGroups | p99 | 43ms | 8ms | -35ms | -80.86
| LinkMetadataStore.Get | p99 | 24ms | 5ms | -19ms | -80.61
| ChannelStore.SaveMember | p99 | 246ms | 48ms | -198ms | -80.41
| ChannelStore.IncrementMentionCount | p99 | 25ms | 5ms | -20ms | -80.20
| ChannelStore.GetChannelsByUser | p99 | 49ms | 10ms | -39ms | -79.49
| ChannelStore.CreateDirectChannel | p99 | 121ms | 25ms | -96ms | -79.33
| FileInfoStore.GetByIds | p99 | 49ms | 10ms | -39ms | -79.06
| PostAcknowledgementStore.GetForPosts | p99 | 42ms | 9ms | -33ms | -78.98
| PostStore.GetPostReminderMetadata | p99 | 22ms | 5ms | -17ms | -78.74
| DraftStore.Delete | p99 | 23ms | 5ms | -18ms | -78.53
| ReactionStore.GetForPost | p99 | 41ms | 9ms | -32ms | -78.53
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 24ms | 5ms | -19ms | -78.49
| UserStore.Count | p99 | 460ms | 99ms | -361ms | -78.48
| PostStore.GetPostIdAfterTime | p99 | 22ms | 5ms | -17ms | -78.43
| PostStore.GetSingle | p99 | 22ms | 5ms | -17ms | -78.37
| UserStore.GetUnreadCount | p99 | 46ms | 10ms | -36ms | -77.42
| SystemStore.GetByName | p99 | 22ms | 5ms | -17ms | -76.88
| ProductNoticesStore.View | p99 | 214ms | 50ms | -164ms | -76.68
| PostStore.GetPostIdBeforeTime | p99 | 22ms | 5ms | -17ms | -76.60
| ThreadStore.GetThreadForUser | p99 | 43ms | 10ms | -33ms | -76.18
| TeamStore.Get | p99 | 22ms | 5ms | -17ms | -76.05
| SessionStore.UpdateLastActivityAt | p99 | 20ms | 5ms | -15ms | -75.81
| PostPersistentNotificationStore.Get | p99 | 19ms | 5ms | -14ms | -75.47
| PostPersistentNotificationStore.DeleteExpired | p99 | 19ms | 5ms | -14ms | -75.47
| PluginStore.Delete | p99 | 19ms | 5ms | -14ms | -75.10
| UserStore.UpdateFailedPasswordAttempts | p99 | 33ms | 8ms | -25ms | -74.71
| ThreadStore.MarkAsRead | p99 | 19ms | 5ms | -14ms | -74.55
| ChannelStore.GetPinnedPostCount | p99 | 21ms | 5ms | -16ms | -74.46
| FileInfoStore.AttachToPost | p99 | 39ms | 10ms | -29ms | -73.85
| PostStore.GetPostsByThread | p99 | 20ms | 5ms | -15ms | -73.47
| FileInfoStore.SetContent | p99 | 36ms | 10ms | -26ms | -73.04
| ChannelStore.GetChannelUnread | p99 | 19ms | 5ms | -14ms | -72.84
| PluginStore.SetWithOptions | p99 | 35ms | 10ms | -25ms | -72.42
| ThreadStore.UpdateMembership | p99 | 18ms | 5ms | -13ms | -71.73
| PostStore.GetPostsSince | p99 | 85ms | 24ms | -61ms | -71.70
| ChannelStore.CreateInitialSidebarCategories | p99 | 150ms | 45ms | -105ms | -69.87
| ChannelStore.UpdateLastViewedAt | p99 | 32ms | 10ms | -22ms | -69.29
| PreferenceStore.Save | p99 | 77ms | 24ms | -53ms | -69.05
| ThreadStore.MaintainMembership | p99 | 35ms | 11ms | -24ms | -68.75
| ThreadStore.Get | p99 | 16ms | 5ms | -11ms | -67.44
| ThreadStore.GetThreadUnreadReplyCount | p99 | 23ms | 8ms | -15ms | -65.28
| ChannelStore.GetPublicChannelsForTeam | p99 | 72ms | 25ms | -47ms | -64.87
| UserStore.UpdateLastLogin | p99 | 22ms | 8ms | -14ms | -64.52
| FileInfoStore.GetForPost | p99 | 24ms | 9ms | -15ms | -63.57
| PostStore.GetPostsAfter | p99 | 14ms | 5ms | -9ms | -63.18
| JobStore.UpdateStatus | p99 | 14ms | 5ms | -9ms | -62.72
| UserStore.UpdateUpdateAt | p99 | 25ms | 10ms | -15ms | -60.10
| PostStore.Update | p99 | 62ms | 25ms | -37ms | -59.69
| StatusStore.UpdateExpiredDNDStatuses | p99 | 24ms | 10ms | -14ms | -59.07
| StatusStore.SaveOrUpdate | p99 | 299ms | 126ms | -173ms | -57.93
| TeamStore.SaveMember | p99 | 232ms | 100ms | -132ms | -56.83
| UserStore.Save | p99 | 228ms | 100ms | -128ms | -56.14
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 23ms | 10ms | -13ms | -55.51
| JobStore.UpdateStatusOptimistically | p99 | 23ms | 10ms | -13ms | -55.37
| UserStore.GetAllProfilesInChannel | p99 | 984ms | 492ms | -492ms | -49.98
| PostStore.Save | p99 | 74ms | 37ms | -37ms | -49.88
| ThreadStore.MarkAllAsReadByChannels | p99 | 10ms | 5ms | -5ms | -48.34
| ChannelStore.GetMemberCount | p99 | 457ms | 239ms | -218ms | -47.67
| JobStore.Save | p99 | 9ms | 5ms | -4ms | -43.90
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 9ms | 5ms | -4ms | -42.86
| RoleStore.ChannelHigherScopedPermissions | p99 | 8ms | 5ms | -3ms | -39.18
| AuditStore.Save | p99 | 27ms | 17ms | -10ms | -36.50
| ChannelStore.Save | p99 | 73ms | 49ms | -24ms | -32.88
| UserStore.Search | p99 | 303ms | 204ms | -99ms | -32.68
| StatusStore.UpdateLastActivityAt | p99 | 20ms | 14ms | -6ms | -29.38
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 130ms | 95ms | -35ms | -26.93
| UserStore.AutocompleteUsersInChannel | p99 | 478ms | 351ms | -127ms | -26.55
| ChannelStore.Autocomplete | p99 | 3.251s | 2.455s | -796ms | -24.49
| ChannelStore.GetAllChannelMembersForUser | p99 | 48ms | 38ms | -10ms | -20.83
| PostStore.GetPosts | p99 | 57ms | 49ms | -8ms | -13.97
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createPost | avg | 323ms | 855ms | 532ms | 164.66
| searchPostsInTeam | avg | 56ms | 125ms | 69ms | 122.98
| getChannelStats | avg | 13ms | 15ms | 2ms | 15.97
| getProfileImage | avg | 66ms | 75ms | 9ms | 13.54
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createPost | p99 | 1.802s | 5.987s | 4.185s | 232.25
| searchPostsInTeam | p99 | 469ms | 477ms | 8ms | 1.71
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | avg | 13ms | 0s | -13ms | -103.37
| updateCategoriesForTeamForUser | avg | 45ms | 0s | -45ms | -100.02
| createCategoryForTeamForUser | avg | 20ms | 0s | -20ms | -100.00
| createChannel | avg | 227ms | 0s | -227ms | -99.93
| getTeamStats | avg | 139ms | 0s | -139ms | -99.80
| updateChannelBookmark | avg | 2ms | 0s | -2ms | -99.17
| logout | avg | 47ms | 0s | -47ms | -99.10
| deleteChannelBookmark | avg | 19ms | 0s | -19ms | -98.51
| setPostReminder | avg | 22ms | 0s | -22ms | -98.42
| deletePost | avg | 20ms | 0s | -20ms | -98.24
| getTeamScheduledPosts | avg | 8ms | 0s | -8ms | -97.97
| createChannelBookmark | avg | 14ms | 0s | -14ms | -96.92
| createSchedulePost | avg | 6ms | 0s | -6ms | -92.66
| updateReadStateAllThreadsByUser | avg | 2ms | 0s | -2ms | -84.84
| getUsers | avg | 5ms | 1ms | -4ms | -78.72
| createGroupChannel | avg | 337ms | 90ms | -247ms | -73.29
| getUser | avg | 6ms | 2ms | -4ms | -71.80
| getPreferences | avg | 6ms | 2ms | -4ms | -71.40
| createDirectChannel | avg | 214ms | 66ms | -148ms | -69.28
| getPostsForChannel | avg | 35ms | 12ms | -23ms | -66.66
| getTeamMembersForUser | avg | 5ms | 2ms | -3ms | -65.72
| getThreadsForUser | avg | 5ms | 2ms | -3ms | -62.84
| getAllTeams | avg | 5ms | 2ms | -3ms | -60.12
| removeUserCustomStatus | avg | 148ms | 61ms | -87ms | -58.75
| deleteDraft | avg | 4ms | 2ms | -2ms | -56.21
| addChannelMember | avg | 207ms | 98ms | -109ms | -52.73
| getTeamsUnreadForUser | avg | 8ms | 4ms | -4ms | -51.82
| getCategoriesForTeamForUser | avg | 14ms | 7ms | -7ms | -51.60
| getUsersByNames | avg | 4ms | 2ms | -2ms | -50.86
| getDrafts | avg | 4ms | 2ms | -2ms | -49.60
| searchGroupChannels | avg | 4ms | 2ms | -2ms | -48.51
| getChannelsForTeamForUser | avg | 4ms | 2ms | -2ms | -47.86
| getChannelsForUser | avg | 4ms | 2ms | -2ms | -47.32
| getTeamsForUser | avg | 4ms | 2ms | -2ms | -44.57
| viewChannel | avg | 17ms | 10ms | -7ms | -42.10
| getChannelMembersForUser | avg | 5ms | 3ms | -2ms | -40.79
| createUser | avg | 160ms | 97ms | -63ms | -39.37
| addTeamMember | avg | 974ms | 617ms | -357ms | -36.65
| autocompleteUsers | avg | 151ms | 100ms | -51ms | -33.69
| getChannelMember | avg | 7ms | 5ms | -2ms | -27.21
| getClientConfig | avg | 7ms | 5ms | -2ms | -27.04
| saveReaction | avg | 11ms | 8ms | -3ms | -26.14
| autocompleteChannelsForTeamForSearch | avg | 157ms | 121ms | -36ms | -23.00
| getPostThread | avg | 15ms | 12ms | -3ms | -19.80
| patchPost | avg | 35ms | 29ms | -6ms | -17.05
| updateReadStateThreadByUser | avg | 31ms | 26ms | -5ms | -16.27
| getPostsForChannelAroundLastUnread | avg | 28ms | 24ms | -4ms | -14.40
| searchUsers | avg | 47ms | 42ms | -5ms | -10.72
| searchAllChannels | avg | 1.02s | 914ms | -106ms | -10.39
| login | avg | 77ms | 70ms | -7ms | -9.09
| uploadFileStream | avg | 384ms | 351ms | -33ms | -8.59
| getFileThumbnail | avg | 34ms | 32ms | -2ms | -5.93
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| updateChannelBookmark | p99 | 5ms | 0s | -5ms | -101.01
| createChannelBookmark | p99 | 46ms | 0s | -46ms | -100.98
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -100.96
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| getTeamStats | p99 | 249ms | 0s | -249ms | -100.20
| updateCategoriesForTeamForUser | p99 | 215ms | 0s | -215ms | -100.12
| createChannel | p99 | 478ms | 0s | -478ms | -100.09
| setPostReminder | p99 | 215ms | 0s | -215ms | -100.09
| createSchedulePost | p99 | 45ms | 0s | -45ms | -100.00
| followThreadByUser | p99 | 45ms | 0s | -45ms | -100.00
| logout | p99 | 231ms | 0s | -231ms | -99.89
| deletePost | p99 | 48ms | 0s | -48ms | -99.74
| getTeamScheduledPosts | p99 | 95ms | 0s | -95ms | -99.66
| getCategoriesForTeamForUser | p99 | 173ms | 10ms | -163ms | -94.31
| getPreferences | p99 | 80ms | 5ms | -75ms | -94.22
| getAllTeams | p99 | 67ms | 5ms | -62ms | -92.42
| getTeamMembersForUser | p99 | 59ms | 5ms | -54ms | -92.26
| getTeamsForUser | p99 | 60ms | 5ms | -55ms | -91.89
| getThreadsForUser | p99 | 57ms | 5ms | -52ms | -91.71
| getChannelsForTeamForUser | p99 | 48ms | 5ms | -43ms | -90.41
| getDrafts | p99 | 45ms | 5ms | -40ms | -89.86
| getChannelMembersForTeamForUser | p99 | 45ms | 5ms | -40ms | -89.83
| createGroupChannel | p99 | 983ms | 100ms | -883ms | -89.79
| searchGroupChannels | p99 | 46ms | 5ms | -41ms | -89.78
| getChannelMembersForUser | p99 | 51ms | 5ms | -46ms | -89.76
| getTeamsUnreadForUser | p99 | 93ms | 10ms | -83ms | -89.65
| getUser | p99 | 84ms | 9ms | -75ms | -88.87
| autocompleteChannelsForTeamForSearch | p99 | 2.052s | 247ms | -1.805s | -87.98
| getUsersByNames | p99 | 42ms | 5ms | -37ms | -87.81
| listChannelBookmarksForChannel | p99 | 33ms | 5ms | -28ms | -86.15
| getUsers | p99 | 51ms | 7ms | -44ms | -85.45
| saveReaction | p99 | 117ms | 17ms | -100ms | -85.37
| getClientConfig | p99 | 63ms | 10ms | -53ms | -84.47
| getChannelMember | p99 | 89ms | 16ms | -73ms | -82.46
| getChannel | p99 | 132ms | 24ms | -108ms | -81.82
| viewChannel | p99 | 133ms | 25ms | -108ms | -80.92
| getChannelsForUser | p99 | 50ms | 10ms | -40ms | -80.76
| getPostsForChannel | p99 | 245ms | 48ms | -197ms | -80.50
| createDirectChannel | p99 | 492ms | 100ms | -392ms | -79.67
| deleteDraft | p99 | 42ms | 9ms | -33ms | -79.51
| upsertDraft | p99 | 42ms | 10ms | -32ms | -77.05
| patchPost | p99 | 212ms | 50ms | -162ms | -76.42
| addTeamMember | p99 | 3.826s | 995ms | -2.831s | -73.99
| getPostThread | p99 | 96ms | 25ms | -71ms | -73.65
| updateReadStateThreadByUser | p99 | 186ms | 50ms | -136ms | -73.17
| getTeamMember | p99 | 30ms | 9ms | -21ms | -71.04
| unfollowThreadByUser | p99 | 83ms | 25ms | -58ms | -69.64
| getPostsForChannelAroundLastUnread | p99 | 245ms | 81ms | -164ms | -66.99
| getPublicChannelsForTeam | p99 | 72ms | 25ms | -47ms | -64.87
| getChannelUnread | p99 | 21ms | 9ms | -12ms | -58.48
| updatePreferences | p99 | 49ms | 24ms | -25ms | -50.83
| addChannelMember | p99 | 498ms | 246ms | -252ms | -50.55
| createUser | p99 | 488ms | 244ms | -244ms | -50.00
| removeUserCustomStatus | p99 | 469ms | 246ms | -223ms | -47.56
| getUsersByIds | p99 | 8ms | 5ms | -3ms | -36.52
| login | p99 | 381ms | 246ms | -135ms | -35.43
| autocompleteUsers | p99 | 473ms | 321ms | -152ms | -32.15
| searchUsers | p99 | 306ms | 213ms | -93ms | -30.42
| searchAllChannels | p99 | 3.251s | 2.455s | -796ms | -24.49
| getChannelStats | p99 | 241ms | 218ms | -23ms | -9.54
| getFileThumbnail | p99 | 97ms | 90ms | -7ms | -7.25
| getProfileImage | p99 | 263ms | 248ms | -15ms | -5.70
| getFilePreview | p99 | 100ms | 97ms | -3ms | -3.01
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 3ms | -1ms | -23.550
| |  P99| 27ms| 17ms | -10ms | -36.504
| BotStore.Get |  Avg| 3ms| 4ms | 1ms | 30.872
| |  P99| 23ms| 24ms | 1ms | 4.353
| ChannelBookmarkStore.Delete |  Avg| 6ms| 0s | -6ms | -106.434
| |  P99| 10ms| 0s | -10ms | -100.671
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -99.269
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 2ms | -1ms | -32.277
| |  P99| 29ms| 5ms | -24ms | -84.077
| ChannelBookmarkStore.Save |  Avg| 9ms| 0s | -9ms | -96.212
| |  P99| 24ms| 0s | -24ms | -98.005
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 3ms | -1ms | -25.995
| |  P99| 23ms| 10ms | -13ms | -55.513
| ChannelStore.Autocomplete |  Avg| 1.019s| 914ms | -105ms | -10.300
| |  P99| 3.251s| 2.455s | -796ms | -24.485
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 156ms| 121ms | -35ms | -22.369
| |  P99| 2.052s| 247ms | -1.805s | -87.978
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 20ms | -4ms | -16.749
| |  P99| 121ms| 25ms | -96ms | -79.330
| ChannelStore.CreateInitialSidebarCategories |  Avg| 23ms| 18ms | -5ms | -21.718
| |  P99| 150ms| 45ms | -105ms | -69.874
| ChannelStore.CreateSidebarCategory |  Avg| 18ms| 0s | -18ms | -102.182
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 5ms| 2ms | -3ms | -62.412
| |  P99| 77ms| 5ms | -72ms | -93.245
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 7ms | 2ms | 42.122
| |  P99| 48ms| 38ms | -10ms | -20.832
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 27ms | 13ms | 89.675
| |  P99| 130ms| 95ms | -35ms | -26.927
| ChannelStore.GetByName |  Avg| 7ms| 3ms | -4ms | -54.870
| |  P99| 78ms| 9ms | -69ms | -88.657
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -39.337
| |  P99| 19ms| 5ms | -14ms | -72.840
| ChannelStore.GetChannels |  Avg| 4ms| 2ms | -2ms | -49.169
| |  P99| 47ms| 5ms | -42ms | -88.733
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 2ms | -2ms | -48.583
| |  P99| 49ms| 10ms | -39ms | -79.490
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 2ms | -1ms | -31.227
| |  P99| 33ms| 5ms | -28ms | -84.730
| ChannelStore.GetFileCount |  Avg| 5ms| 2ms | -3ms | -57.095
| |  P99| 44ms| 5ms | -39ms | -87.911
| ChannelStore.GetGuestCount |  Avg| 5ms| 2ms | -3ms | -57.481
| |  P99| 76ms| 6ms | -70ms | -92.148
| ChannelStore.GetMember |  Avg| 3ms| 2ms | -1ms | -33.532
| |  P99| 30ms| 5ms | -25ms | -83.110
| ChannelStore.GetMemberCount |  Avg| 105ms| 57ms | -48ms | -45.568
| |  P99| 457ms| 239ms | -218ms | -47.673
| ChannelStore.GetMemberForPost |  Avg| 4ms| 2ms | -2ms | -55.973
| |  P99| 40ms| 5ms | -35ms | -86.590
| ChannelStore.GetMemberLastViewedAt |  Avg| 4ms| 2ms | -2ms | -50.696
| |  P99| 49ms| 5ms | -44ms | -89.123
| ChannelStore.GetMembersForUser |  Avg| 4ms| 3ms | -1ms | -25.106
| |  P99| 44ms| 5ms | -39ms | -88.307
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 3ms | -2ms | -41.701
| |  P99| 50ms| 5ms | -45ms | -89.662
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 2ms | -1ms | -36.196
| |  P99| 21ms| 5ms | -16ms | -74.464
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 72ms| 25ms | -47ms | -64.867
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 13ms| 7ms | -6ms | -46.699
| |  P99| 166ms| 10ms | -156ms | -94.242
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 0s | -6ms | -98.537
| |  P99| 77ms| 0s | -77ms | -100.652
| ChannelStore.GetTeamChannels |  Avg| 25ms| 0s | -25ms | -101.781
| |  P99| 48ms| 0s | -48ms | -100.503
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 2ms | -1ms | -36.401
| |  P99| 25ms| 5ms | -20ms | -80.204
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 0s | -2ms | -106.635
| |  P99| 23ms| 0s | -23ms | -100.791
| ChannelStore.Save |  Avg| 14ms| 22ms | 8ms | 55.520
| |  P99| 73ms| 49ms | -24ms | -32.880
| ChannelStore.SaveMember |  Avg| 36ms| 24ms | -12ms | -33.689
| |  P99| 246ms| 48ms | -198ms | -80.407
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 2ms | -2ms | -49.498
| |  P99| 45ms| 5ms | -40ms | -88.922
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 5ms | -1ms | -16.354
| |  P99| 32ms| 10ms | -22ms | -69.291
| ChannelStore.UpdateSidebarCategories |  Avg| 30ms| 0s | -30ms | -99.446
| |  P99| 179ms| 0s | -179ms | -99.734
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.863
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 3ms | -2ms | -40.877
| |  P99| 46ms| 5ms | -41ms | -88.894
| CommandWebhookStore.Cleanup |  Avg| 2ms| 0s | -2ms | -120.682
| |  P99| 5ms| 0s | -5ms | -101.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 0s | -2ms | -121.879
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Delete |  Avg| 4ms| 3ms | -1ms | -26.463
| |  P99| 23ms| 5ms | -18ms | -78.531
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 22ms| 0s | -22ms | -98.290
| |  P99| 93ms| 0s | -93ms | -100.540
| DraftStore.Get |  Avg| 3ms| 2ms | -1ms | -30.259
| |  P99| 40ms| 5ms | -35ms | -87.130
| DraftStore.GetDraftsForUser |  Avg| 4ms| 2ms | -2ms | -51.906
| |  P99| 44ms| 5ms | -39ms | -88.112
| DraftStore.Upsert |  Avg| 4ms| 3ms | -1ms | -24.897
| |  P99| 31ms| 5ms | -26ms | -84.115
| EmojiStore.GetByName |  Avg| 3ms| 2ms | -1ms | -32.401
| |  P99| 33ms| 5ms | -28ms | -85.362
| EmojiStore.GetMultipleByName |  Avg| 2ms| 0s | -2ms | -104.473
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 6ms| 5ms | -1ms | -15.987
| |  P99| 39ms| 10ms | -29ms | -73.849
| FileInfoStore.Get |  Avg| 3ms| 2ms | -1ms | -33.800
| |  P99| 29ms| 5ms | -24ms | -83.634
| FileInfoStore.GetByIds |  Avg| 4ms| 5ms | 1ms | 27.900
| |  P99| 49ms| 10ms | -39ms | -79.059
| FileInfoStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 9ms | -15ms | -63.567
| FileInfoStore.Save |  Avg| 5ms| 4ms | -1ms | -19.886
| |  P99| 35ms| 5ms | -30ms | -86.644
| FileInfoStore.SetContent |  Avg| 9ms| 7ms | -2ms | -23.203
| |  P99| 36ms| 10ms | -26ms | -73.038
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 2ms | -2ms | -52.593
| |  P99| 48ms| 5ms | -43ms | -88.668
| GroupStore.GetByName |  Avg| 5ms| 2ms | -3ms | -61.771
| |  P99| 77ms| 5ms | -72ms | -93.097
| GroupStore.GetGroups |  Avg| 4ms| 2ms | -2ms | -52.506
| |  P99| 43ms| 8ms | -35ms | -80.858
| JobStore.GetAllByStatus |  Avg| 4ms| 2ms | -2ms | -49.206
| |  P99| 48ms| 5ms | -43ms | -89.680
| JobStore.GetCountByStatusAndType |  Avg| 6ms| 2ms | -4ms | -66.281
| |  P99| 141ms| 5ms | -136ms | -96.797
| JobStore.GetNewestJobByStatusesAndType |  Avg| 6ms| 3ms | -3ms | -52.612
| |  P99| 92ms| 5ms | -87ms | -94.224
| JobStore.Save |  Avg| 4ms| 3ms | -1ms | -27.804
| |  P99| 9ms| 5ms | -4ms | -43.896
| JobStore.UpdateOptimistically |  Avg| 4ms| 3ms | -1ms | -25.332
| |  P99| 64ms| 5ms | -59ms | -91.473
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -26.573
| |  P99| 14ms| 5ms | -9ms | -62.718
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 4ms | -4ms | -52.122
| |  P99| 23ms| 10ms | -13ms | -55.370
| LinkMetadataStore.Get |  Avg| 3ms| 2ms | -1ms | -35.617
| |  P99| 24ms| 5ms | -19ms | -80.608
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 2ms | -1ms | -38.469
| |  P99| 19ms| 5ms | -14ms | -75.101
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 5ms| 2ms | -3ms | -65.090
| |  P99| 74ms| 5ms | -69ms | -93.254
| PluginStore.SetWithOptions |  Avg| 6ms| 5ms | -1ms | -17.126
| |  P99| 35ms| 10ms | -25ms | -72.422
| PostAcknowledgementStore.GetForPost |  Avg| 4ms| 2ms | -2ms | -50.200
| |  P99| 57ms| 5ms | -52ms | -91.221
| PostAcknowledgementStore.GetForPosts |  Avg| 5ms| 2ms | -3ms | -63.195
| |  P99| 42ms| 9ms | -33ms | -78.983
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -75.472
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -75.472
| PostPersistentNotificationStore.GetSingle |  Avg| 3ms| 2ms | -1ms | -32.328
| |  P99| 38ms| 5ms | -33ms | -87.743
| PostPriorityStore.GetForPost |  Avg| 4ms| 2ms | -2ms | -51.694
| |  P99| 42ms| 5ms | -37ms | -87.779
| PostPriorityStore.GetForPosts |  Avg| 5ms| 2ms | -3ms | -61.538
| |  P99| 46ms| 9ms | -37ms | -81.253
| PostStore.AnalyticsPostCount |  Avg| 822ms| 0s | -822ms | -100.005
| |  P99| 995ms| 0s | -995ms | -99.997
| PostStore.Delete |  Avg| 14ms| 0s | -14ms | -100.834
| |  P99| 25ms| 0s | -25ms | -100.604
| PostStore.Get |  Avg| 7ms| 5ms | -2ms | -30.153
| |  P99| 58ms| 10ms | -48ms | -82.150
| PostStore.GetEtag |  Avg| 5ms| 2ms | -3ms | -64.011
| |  P99| 67ms| 7ms | -60ms | -89.391
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -78.431
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -76.600
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 2ms | -1ms | -37.108
| |  P99| 22ms| 5ms | -17ms | -78.737
| PostStore.GetPostReminders |  Avg| 8ms| 6ms | -2ms | -24.103
| |  P99| 87ms| 10ms | -77ms | -88.506
| PostStore.GetPosts |  Avg| 6ms| 8ms | 2ms | 34.540
| |  P99| 57ms| 49ms | -8ms | -13.973
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 5ms | -9ms | -63.179
| PostStore.GetPostsBefore |  Avg| 5ms| 3ms | -2ms | -41.444
| |  P99| 46ms| 5ms | -41ms | -89.214
| PostStore.GetPostsByThread |  Avg| 3ms| 2ms | -1ms | -36.099
| |  P99| 20ms| 5ms | -15ms | -73.467
| PostStore.GetPostsSince |  Avg| 12ms| 5ms | -7ms | -57.301
| |  P99| 85ms| 24ms | -61ms | -71.701
| PostStore.GetSingle |  Avg| 3ms| 2ms | -1ms | -35.080
| |  P99| 22ms| 5ms | -17ms | -78.373
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 11ms | -2ms | -14.868
| |  P99| 74ms| 37ms | -37ms | -49.881
| PostStore.SearchPostsForUser |  Avg| 48ms| 107ms | 59ms | 122.650
| |  P99| 380ms| 455ms | 75ms | 19.753
| PostStore.SetPostReminder |  Avg| 8ms| 0s | -8ms | -97.316
| |  P99| 44ms| 0s | -44ms | -99.995
| PostStore.Update |  Avg| 16ms| 15ms | -1ms | -6.408
| |  P99| 62ms| 25ms | -37ms | -59.689
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 0s | -3ms | -114.535
| |  P99| 9ms| 0s | -9ms | -97.296
| PreferenceStore.Get |  Avg| 4ms| 2ms | -2ms | -55.531
| |  P99| 42ms| 5ms | -37ms | -88.720
| PreferenceStore.GetAll |  Avg| 5ms| 2ms | -3ms | -55.191
| |  P99| 79ms| 5ms | -74ms | -94.137
| PreferenceStore.Save |  Avg| 11ms| 9ms | -2ms | -18.124
| |  P99| 77ms| 24ms | -53ms | -69.047
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 0s | -2ms | -102.772
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 38ms| 26ms | -12ms | -31.872
| |  P99| 214ms| 50ms | -164ms | -76.677
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 9ms | -32ms | -78.529
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.179
| RoleStore.GetByNames |  Avg| 12ms| 0s | -12ms | -102.431
| |  P99| 48ms| 5ms | -43ms | -89.444
| ScheduledPostStore.CreateScheduledPost |  Avg| 6ms| 0s | -6ms | -108.228
| |  P99| 40ms| 0s | -40ms | -99.994
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 7ms| 0s | -7ms | -104.415
| |  P99| 87ms| 0s | -87ms | -100.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 4ms| 0s | -4ms | -100.442
| |  P99| 48ms| 0s | -48ms | -98.970
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 0s | -3ms | -110.557
| |  P99| 23ms| 0s | -23ms | -99.783
| SessionStore.Get |  Avg| 8ms| 4ms | -4ms | -52.072
| |  P99| 85ms| 10ms | -75ms | -88.445
| SessionStore.GetLRUSessions |  Avg| 4ms| 2ms | -2ms | -49.114
| |  P99| 62ms| 5ms | -57ms | -92.430
| SessionStore.GetSessionsExpired |  Avg| 8ms| 2ms | -6ms | -72.636
| |  P99| 95ms| 5ms | -90ms | -95.238
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 2ms | -1ms | -30.419
| |  P99| 24ms| 5ms | -19ms | -78.492
| SessionStore.Remove |  Avg| 5ms| 0s | -5ms | -97.626
| |  P99| 23ms| 0s | -23ms | -99.462
| SessionStore.Save |  Avg| 8ms| 6ms | -2ms | -24.727
| |  P99| 72ms| 13ms | -59ms | -81.820
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 3ms | -1ms | -27.176
| |  P99| 20ms| 5ms | -15ms | -75.807
| SharedChannelStore.HasChannel |  Avg| 3ms| 0s | -3ms | -104.323
| |  P99| 27ms| 0s | -27ms | -101.762
| StatusStore.Get |  Avg| 4ms| 2ms | -2ms | -52.348
| |  P99| 48ms| 6ms | -42ms | -88.263
| StatusStore.GetByIds |  Avg| 3ms| 2ms | -1ms | -33.668
| |  P99| 27ms| 5ms | -22ms | -82.967
| StatusStore.SaveOrUpdate |  Avg| 12ms| 13ms | 1ms | 8.139
| |  P99| 299ms| 126ms | -173ms | -57.926
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 6ms | -1ms | -14.128
| |  P99| 24ms| 10ms | -14ms | -59.072
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 3ms | -1ms | -28.081
| |  P99| 20ms| 14ms | -6ms | -29.382
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -76.876
| TeamStore.Get |  Avg| 3ms| 2ms | -1ms | -36.912
| |  P99| 22ms| 5ms | -17ms | -76.053
| TeamStore.GetActiveMemberCount |  Avg| 139ms| 0s | -139ms | -99.863
| |  P99| 249ms| 0s | -249ms | -100.201
| TeamStore.GetAllPage |  Avg| 4ms| 2ms | -2ms | -46.558
| |  P99| 57ms| 5ms | -52ms | -91.457
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 2ms | -2ms | -47.569
| |  P99| 49ms| 5ms | -44ms | -88.892
| TeamStore.GetMember |  Avg| 3ms| 2ms | -1ms | -33.010
| |  P99| 32ms| 5ms | -27ms | -84.342
| TeamStore.GetTeamsByUserId |  Avg| 4ms| 2ms | -2ms | -45.542
| |  P99| 58ms| 5ms | -53ms | -91.143
| TeamStore.GetTeamsForUser |  Avg| 4ms| 2ms | -2ms | -48.598
| |  P99| 51ms| 5ms | -46ms | -90.795
| TeamStore.GetTotalMemberCount |  Avg| 108ms| 0s | -108ms | -99.995
| |  P99| 247ms| 0s | -247ms | -99.879
| TeamStore.SaveMember |  Avg| 80ms| 64ms | -16ms | -20.121
| |  P99| 232ms| 100ms | -132ms | -56.829
| ThreadStore.Get |  Avg| 3ms| 2ms | -1ms | -35.602
| |  P99| 16ms| 5ms | -11ms | -67.441
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 2ms | -1ms | -32.071
| |  P99| 32ms| 5ms | -27ms | -84.423
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 2ms | -3ms | -63.974
| |  P99| 61ms| 5ms | -56ms | -92.511
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 2ms | -1ms | -29.430
| |  P99| 42ms| 5ms | -37ms | -87.748
| ThreadStore.GetThreadForUser |  Avg| 5ms| 4ms | -1ms | -19.025
| |  P99| 43ms| 10ms | -33ms | -76.182
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 2ms | -1ms | -33.871
| |  P99| 23ms| 8ms | -15ms | -65.281
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 3ms | -1ms | -23.674
| |  P99| 47ms| 5ms | -42ms | -89.402
| ThreadStore.GetTotalThreads |  Avg| 4ms| 2ms | -2ms | -49.821
| |  P99| 49ms| 5ms | -44ms | -89.063
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 2ms | -2ms | -49.675
| |  P99| 48ms| 5ms | -43ms | -89.578
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 2ms | -2ms | -49.691
| |  P99| 50ms| 5ms | -45ms | -90.516
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 2ms | -2ms | -48.293
| |  P99| 53ms| 5ms | -48ms | -90.051
| ThreadStore.MaintainMembership |  Avg| 7ms| 6ms | -1ms | -14.898
| |  P99| 35ms| 11ms | -24ms | -68.745
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -48.335
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 0s | -2ms | -87.870
| |  P99| 5ms| 0s | -5ms | -100.957
| ThreadStore.MarkAsRead |  Avg| 4ms| 3ms | -1ms | -26.646
| |  P99| 19ms| 5ms | -14ms | -74.548
| ThreadStore.UpdateMembership |  Avg| 4ms| 3ms | -1ms | -28.231
| |  P99| 18ms| 5ms | -13ms | -71.732
| TokenStore.Cleanup |  Avg| 2ms| 0s | -2ms | -118.701
| |  P99| 5ms| 0s | -5ms | -101.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 0s | -2ms | -86.059
| |  P99| 8ms| 0s | -8ms | -94.678
| UserStore.AutocompleteUsersInChannel |  Avg| 180ms| 115ms | -65ms | -36.023
| |  P99| 478ms| 351ms | -127ms | -26.545
| UserStore.Count |  Avg| 105ms| 50ms | -55ms | -52.576
| |  P99| 460ms| 99ms | -361ms | -78.479
| UserStore.Get |  Avg| 3ms| 2ms | -1ms | -35.329
| |  P99| 25ms| 5ms | -20ms | -81.175
| UserStore.GetAllProfiles |  Avg| 5ms| 3ms | -2ms | -44.292
| |  P99| 45ms| 5ms | -40ms | -88.118
| UserStore.GetAllProfilesInChannel |  Avg| 356ms| 178ms | -178ms | -49.991
| |  P99| 984ms| 492ms | -492ms | -49.982
| UserStore.GetByUsername |  Avg| 3ms| 2ms | -1ms | -29.312
| |  P99| 39ms| 5ms | -34ms | -87.944
| UserStore.GetForLogin |  Avg| 5ms| 2ms | -3ms | -65.134
| |  P99| 67ms| 5ms | -62ms | -93.077
| UserStore.GetMany |  Avg| 4ms| 2ms | -2ms | -50.250
| |  P99| 76ms| 5ms | -71ms | -94.030
| UserStore.GetProfileByIds |  Avg| 3ms| 2ms | -1ms | -30.412
| |  P99| 39ms| 5ms | -34ms | -86.934
| UserStore.GetProfilesByUsernames |  Avg| 4ms| 2ms | -2ms | -53.217
| |  P99| 42ms| 5ms | -37ms | -88.983
| UserStore.GetProfilesInChannel |  Avg| 2ms| 0s | -2ms | -88.119
| |  P99| 5ms| 0s | -5ms | -100.999
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 0s | -5ms | -95.049
| |  P99| 10ms| 0s | -10ms | -101.138
| UserStore.GetUnreadCount |  Avg| 5ms| 3ms | -2ms | -37.023
| |  P99| 46ms| 10ms | -36ms | -77.423
| UserStore.IsEmpty |  Avg| 3ms| 1ms | -2ms | -74.696
| |  P99| 42ms| 5ms | -37ms | -87.244
| UserStore.Save |  Avg| 79ms| 67ms | -12ms | -15.218
| |  P99| 228ms| 100ms | -128ms | -56.140
| UserStore.Search |  Avg| 45ms| 40ms | -5ms | -10.995
| |  P99| 303ms| 204ms | -99ms | -32.676
| UserStore.Update |  Avg| 8ms| 5ms | -3ms | -36.521
| |  P99| 66ms| 10ms | -56ms | -85.159
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 3ms | -1ms | -22.784
| |  P99| 33ms| 8ms | -25ms | -74.710
| UserStore.UpdateLastLogin |  Avg| 4ms| 3ms | -1ms | -25.713
| |  P99| 22ms| 8ms | -14ms | -64.525
| UserStore.UpdateUpdateAt |  Avg| 4ms| 3ms | -1ms | -23.222
| |  P99| 25ms| 10ms | -15ms | -60.104
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 2ms | -2ms | -46.840
| |  P99| 66ms| 5ms | -61ms | -92.344
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 2ms | -5ms | -71.241
| |  P99| 70ms| 5ms | -65ms | -93.453
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 207ms| 98ms | -109ms | -52.731
| | P99| 498ms| 246ms | -252ms | -50.555
| addTeamMember | Avg| 974ms| 617ms | -357ms | -36.651
| | P99| 3.826s| 995ms | -2.831s | -73.990
| autocompleteChannelsForTeamForSearch | Avg| 157ms| 121ms | -36ms | -22.996
| | P99| 2.052s| 247ms | -1.805s | -87.978
| autocompleteUsers | Avg| 151ms| 100ms | -51ms | -33.685
| | P99| 473ms| 321ms | -152ms | -32.145
| createCategoryForTeamForUser | Avg| 20ms| 0s | -20ms | -100.000
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 227ms| 0s | -227ms | -99.932
| | P99| 478ms| 0s | -478ms | -100.088
| createChannelBookmark | Avg| 14ms| 0s | -14ms | -96.920
| | P99| 46ms| 0s | -46ms | -100.976
| createDirectChannel | Avg| 214ms| 66ms | -148ms | -69.276
| | P99| 492ms| 100ms | -392ms | -79.670
| createGroupChannel | Avg| 337ms| 90ms | -247ms | -73.295
| | P99| 983ms| 100ms | -883ms | -89.786
| createPost | Avg| 323ms| 855ms | 532ms | 164.656
| | P99| 1.802s| 5.987s | 4.185s | 232.247
| createSchedulePost | Avg| 6ms| 0s | -6ms | -92.663
| | P99| 45ms| 0s | -45ms | -99.997
| createUser | Avg| 160ms| 97ms | -63ms | -39.373
| | P99| 488ms| 244ms | -244ms | -49.996
| deleteChannelBookmark | Avg| 19ms| 0s | -19ms | -98.513
| | P99| 25ms| 0s | -25ms | -100.604
| deleteDraft | Avg| 4ms| 2ms | -2ms | -56.213
| | P99| 42ms| 9ms | -33ms | -79.513
| deletePost | Avg| 20ms| 0s | -20ms | -98.243
| | P99| 48ms| 0s | -48ms | -99.740
| followThreadByUser | Avg| 13ms| 0s | -13ms | -103.374
| | P99| 45ms| 0s | -45ms | -99.996
| getAllTeams | Avg| 5ms| 2ms | -3ms | -60.121
| | P99| 67ms| 5ms | -62ms | -92.418
| getCategoriesForTeamForUser | Avg| 14ms| 7ms | -7ms | -51.601
| | P99| 173ms| 10ms | -163ms | -94.310
| getChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 132ms| 24ms | -108ms | -81.823
| getChannelMember | Avg| 7ms| 5ms | -2ms | -27.210
| | P99| 89ms| 16ms | -73ms | -82.463
| getChannelMembersForTeamForUser | Avg| 4ms| 3ms | -1ms | -24.482
| | P99| 45ms| 5ms | -40ms | -89.825
| getChannelMembersForUser | Avg| 5ms| 3ms | -2ms | -40.789
| | P99| 51ms| 5ms | -46ms | -89.764
| getChannelStats | Avg| 13ms| 15ms | 2ms | 15.971
| | P99| 241ms| 218ms | -23ms | -9.544
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 9ms | -12ms | -58.483
| getChannelsForTeamForUser | Avg| 4ms| 2ms | -2ms | -47.864
| | P99| 48ms| 5ms | -43ms | -90.415
| getChannelsForUser | Avg| 4ms| 2ms | -2ms | -47.322
| | P99| 50ms| 10ms | -40ms | -80.762
| getClientConfig | Avg| 7ms| 5ms | -2ms | -27.037
| | P99| 63ms| 10ms | -53ms | -84.468
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 4ms| 2ms | -2ms | -49.595
| | P99| 45ms| 5ms | -40ms | -89.865
| getFilePreview | Avg| 40ms| 39ms | -1ms | -2.505
| | P99| 100ms| 97ms | -3ms | -3.010
| getFileThumbnail | Avg| 34ms| 32ms | -2ms | -5.926
| | P99| 97ms| 90ms | -7ms | -7.247
| getPostThread | Avg| 15ms| 12ms | -3ms | -19.800
| | P99| 96ms| 25ms | -71ms | -73.648
| getPostsForChannel | Avg| 35ms| 12ms | -23ms | -66.658
| | P99| 245ms| 48ms | -197ms | -80.496
| getPostsForChannelAroundLastUnread | Avg| 28ms| 24ms | -4ms | -14.404
| | P99| 245ms| 81ms | -164ms | -66.987
| getPreferences | Avg| 6ms| 2ms | -4ms | -71.398
| | P99| 80ms| 5ms | -75ms | -94.215
| getProfileImage | Avg| 66ms| 75ms | 9ms | 13.539
| | P99| 263ms| 248ms | -15ms | -5.704
| getPublicChannelsForTeam | Avg| 14ms| 13ms | -1ms | -7.371
| | P99| 72ms| 25ms | -47ms | -64.867
| getTeamMember | Avg| 3ms| 2ms | -1ms | -34.717
| | P99| 30ms| 9ms | -21ms | -71.038
| getTeamMembersForUser | Avg| 5ms| 2ms | -3ms | -65.722
| | P99| 59ms| 5ms | -54ms | -92.260
| getTeamScheduledPosts | Avg| 8ms| 0s | -8ms | -97.966
| | P99| 95ms| 0s | -95ms | -99.663
| getTeamStats | Avg| 139ms| 0s | -139ms | -99.800
| | P99| 249ms| 0s | -249ms | -100.201
| getTeamsForUser | Avg| 4ms| 2ms | -2ms | -44.570
| | P99| 60ms| 5ms | -55ms | -91.894
| getTeamsUnreadForUser | Avg| 8ms| 4ms | -4ms | -51.822
| | P99| 93ms| 10ms | -83ms | -89.645
| getThreadsForUser | Avg| 5ms| 2ms | -3ms | -62.845
| | P99| 57ms| 5ms | -52ms | -91.709
| getUser | Avg| 6ms| 2ms | -4ms | -71.795
| | P99| 84ms| 9ms | -75ms | -88.872
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 5ms| 1ms | -4ms | -78.717
| | P99| 51ms| 7ms | -44ms | -85.448
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -36.519
| getUsersByNames | Avg| 4ms| 2ms | -2ms | -50.859
| | P99| 42ms| 5ms | -37ms | -87.806
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 2ms | -1ms | -29.612
| | P99| 33ms| 5ms | -28ms | -86.151
| login | Avg| 77ms| 70ms | -7ms | -9.091
| | P99| 381ms| 246ms | -135ms | -35.434
| logout | Avg| 47ms| 0s | -47ms | -99.103
| | P99| 231ms| 0s | -231ms | -99.894
| patchPost | Avg| 35ms| 29ms | -6ms | -17.046
| | P99| 212ms| 50ms | -162ms | -76.416
| removeUserCustomStatus | Avg| 148ms| 61ms | -87ms | -58.754
| | P99| 469ms| 246ms | -223ms | -47.562
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 11ms| 8ms | -3ms | -26.144
| | P99| 117ms| 17ms | -100ms | -85.369
| searchAllChannels | Avg| 1.02s| 914ms | -106ms | -10.395
| | P99| 3.251s| 2.455s | -796ms | -24.485
| searchGroupChannels | Avg| 4ms| 2ms | -2ms | -48.510
| | P99| 46ms| 5ms | -41ms | -89.784
| searchPostsInTeam | Avg| 56ms| 125ms | 69ms | 122.982
| | P99| 469ms| 477ms | 8ms | 1.706
| searchUsers | Avg| 47ms| 42ms | -5ms | -10.725
| | P99| 306ms| 213ms | -93ms | -30.420
| setPostReminder | Avg| 22ms| 0s | -22ms | -98.423
| | P99| 215ms| 0s | -215ms | -100.086
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 83ms| 25ms | -58ms | -69.643
| updateCategoriesForTeamForUser | Avg| 45ms| 0s | -45ms | -100.018
| | P99| 215ms| 0s | -215ms | -100.122
| updateChannelBookmark | Avg| 2ms| 0s | -2ms | -99.171
| | P99| 5ms| 0s | -5ms | -101.010
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 49ms| 24ms | -25ms | -50.831
| updateReadStateAllThreadsByUser | Avg| 2ms| 0s | -2ms | -84.836
| | P99| 5ms| 0s | -5ms | -100.957
| updateReadStateThreadByUser | Avg| 31ms| 26ms | -5ms | -16.272
| | P99| 186ms| 50ms | -136ms | -73.167
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 384ms| 351ms | -33ms | -8.592
| | P99| 984ms| 981ms | -3ms | -0.305
| upsertDraft | Avg| 5ms| 4ms | -1ms | -20.358
| | P99| 42ms| 10ms | -32ms | -77.052
| viewChannel | Avg| 17ms| 10ms | -7ms | -42.099
| | P99| 133ms| 25ms | -108ms | -80.917
